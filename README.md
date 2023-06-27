&nbsp;

<h1 style="text-align: center;"> Isaac Newton Institute: Summer School on Mathematics of Movement  </h1>

<h2 style="text-align: center;"> Abstract </h2>

The purpose of the current study is to establish a modelling framework to understand the movement of European badgers (Meles meles) within their environment. It is widely understood that badgers play a crucial role in the transmission of bovine tuberculosis (bTB), where bTB is a serious disease of cattle and has a significant economic impact on farmers. However, despite all the GPS data, ecologists still do not understand what they can learn from the data about fine-scale badger movement. A key research question we would like to answer is can we generate a dynamical model to explore badger movement?

To model the movements, we are generating a stochastic Brownian motion model using badger GPS tracking data. Such an approach has been successful in describing the movements of free-ranging elk and their avoidance of vehicles and humans but has yet to be applied to the study of badgers. 

The model is created using data driven methods, where it is parametrized using GPS data. The modelling framework will allow us to answer key ecological questions: How does badger movement affect the spread of bTB? How does the weather affect badger movement? With the role badgers play in the spread of bTB, the answer to these questions could be crucial in the role of strategy planning.

We present results on the parameterized model with the data. This includes the generation of an energy potential and the estimation of a noise term. We have also analysed the differences between male and female badgers to understand different transitions. By simulating these differences, we have created a dynamical model that explores badger movement, and we can now start answering the key ecological questions.


---

<h2 style="text-align: center;"> Generated Trajectory </h2>

Below is the animation linked to Figure 3, where the 'badger' can be seen to be moving along its trajectory. The initial position links to an individual badger that is being monitored at the park, and the diffusion term of the badger has been calculated. 

The animation is plotted every two iterations to show a smoother movement of the badger following its trajectory, in comparison to every thirty-five iterations in Figure 3. Also, only the first 10,000 iterations have been animated out of the 100,000 generated. But, this is a great tool to have a better visual of the badger movements in the park.

<p align="center">
<img src="14M_10000.gif">
</p>

---
<h2 style="text-align: center;"> Extended Dynamic Mode Decomposition </h2>

This section compliments the box on Extended Dynamic Mode Decomposition (EDMD). Featured below are the first eight Koopman eigenfunctions that correspond to the first eigenvalues seen in Figure 4. 

<figure>
<p align="center">
<img src="Woodchester_EDMD_K_Eigenfunctions.png">
</p>
      <figcaption> <em>Figure</em>. The first eight eigenfunctions corresponding to the first eight eigenvalues seen in Figure 4. The first eigenfunction (Eigenfunction 0) is constant, as expected. The second eigenfunction (Eigenfunction 1) highlights there are very few transitions between the bottom and the top of the park. The following eigefunctions highlight where the next energy barriers are within the park. </figcaption>
</figure>

When we compare the clustered eigenfunctions against the initial K-Means clustering of the data we see that they are very similar.

<figure>
<p align="center">
<img src = "17_5_Cluster8_2.png" 
      width="400"  />
<img src = "Cluster8_2.png" 
      width="400"  />
      <figcaption> <em>Figure</em>. <b>Left</b>: The eight Koopman eigenfunctions clustered using K-Means. <b>Right</b>: The original GPS data clustered using K-Means clustering. </figcaption>
</p>
</figure>



___
<h2 style="text-align: center;"> Transition Probabilities </h2>


___

<h2 style="text-align: center;"> Bibliography </h2>

[1] Brillinger, D., Preisler, H., Ager, A., Kie, J., and Service, U. *The use of potential functions in modelling animal movement*. Data Analysis from Statistical Foundations: A Festschrift in Honour of the 75th Birthday of DAS Fraser (05 2001).

[2] Burt, W. H. *Territoriality and home range concepts as applied to mammals*. Journal of Mammalogy 24, 3 (1943),
346–352.

[3] Do Linh San, E., Ferrari, N., and Weber, J.M. *Spatio-temporal ecology and density of badgers meles meles in the swiss jura mountains*. European Journal of Wildlife Research 53 (2007), no. 4, 265–275.

[4] Downs, J., Horner, M., Lamb, D., Loraamm, R. W., Anderson, J., and Wood, B. *Testing time-geographic density estimation for home range analysis using an agent-based model of animal movement*. International Journal of Geographical Information Science 32, 7 (2018), 1505–1522.

[5] Klus, S., Koltai, P., and Schutte, C. *On the numerical approximation of the Perron-Frobenius and Koopman operator*. Journal of Computational Dynamics (2015).

[6] Magowan, E.A., Maguire, I.E., Smith, S., Redpath, S., Marks, N.J., Wilson, R.P., Menzies, F., O’Hagan, M., and Scantlebury, D.M., *Dead-reckoning elucidates fine-scale habitat use by European badgers Meles meles*. Animal Biotelemetry 10 (2022), no. 1, 10.

[7] Niemann, J.H., Klus, S., and Schutte, C., *Data-driven model reduction of agent-based systems using the Koopman generator*. PLOS ONE 16 (2021), no. 5, 1–23.

[8] Preisler, H., Ager, A., Johnson, B., and Kie, J. *Modeling animal movements using stochastic differential equations*. Environmetrics 15636 (11 2004), 643–657.

[9] Preisler, H. K., Ager, A. A., and Wisdom, M. J. *Analyzing animal movement patterns using potential functions*.
Ecosphere 4, 3 (2013), 1–13.


