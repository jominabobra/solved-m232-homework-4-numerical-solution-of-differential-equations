Download Link: https://assignmentchef.com/product/solved-m232-homework-4-numerical-solution-of-differential-equations
<br>
<em>This problem allows you to code and compare several different methods we have discussed in class.</em>

Consider the following boundary value problem

<em>u</em><sup>00 </sup>= e<em><sup>x </sup></em>in (0<em>,</em>1)<em>,          u</em>(0) = 3<em>,       u</em><sup>0</sup>(1) = −5<em>.</em>

It has a Dirichlet boundary condition on <em>x </em>= 0 and a Neumann boundary condition on <em>x </em>= 1.

<ul>

 <li>Solve this problem analytically.</li>

 <li>Implement a second-order finite difference method to solve this boundary value problem.Verify that your code is second-order accurate.</li>

 <li>Use your second-order finite difference code from part (b) to compute the extrapolationmethod. Verify that your extrapolation method is fourth-order accurate.</li>

 <li>Use your second-order finite difference code from part (b) to compute the deferred correction solution. Verify that your deferrred correction method is fourth-order accurate.</li>

 <li>Modify your code to implement a fourth-order finite difference method to solve thisboundary value problem (you may want to make extensive use of the Matlab code m). Verify that your code is fourth-order accurate.</li>

 <li>Implement the spectral collocation method on a Chebyshev grid to solve this boundaryvalue problem. You can modify the code SpectralMethod1.m which uses a uniform grid to solve this boundary value problem. Observe that this method is not working well as the number of points increases and then modify this code to use the Chebyshev grid. Verify that your spectral collocation method is now spectrally accurate.</li>

</ul>

For this problem, plot all of your errors versus <em>m</em>, the number of grid points used, on a single graph to compare them to one another. Then give a discussion on your results. For example, what are the costs and benefits to using one method over another with regards to accuracy and efficiency?

2