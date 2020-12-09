# wave_application
Here, we describe the one-dimensional and two-dimensional wave equations with time-varying coefficients that characterize the propagation of waves in a continuous medium. These equations are very important in the fields of engineering and physics, mathematics, and many scientists are working on these equations.
1D model 
	(∂^2 u(t,x))/(∂t^2 )-a(t)(∂^2 u(t,x))/(∂x^2 )+b(t)(∂u(t,x))/∂t+c(t)(∂u(t,x))/∂x+d(t)u(t,x)=f(t,x),   (t,x)∈(0,T)×Ω	(3.1)
 The initial values are given by the initial value condition 
	u(0,x)=φ(x),    ∂u/∂t(0,x)=ψ(x),   (x)∈▁Ω,	(3.2)
 where ▁Ω=(0,X)×(0,Y). Since the domain Ω is bounded we require some conditions on its boundary, for example, the Dirichlet boundary condition 
	u(t,x)|_∂Ω=g(t,x),   t∈[0,T].	(3.3)
 where a(t),b(t),c(t),d(t) are δ- like singularity function as shown below
2D model 
	(∂^2 u(t,x,y))/(∂t^2 )-a(t)((∂^2 u(t,x,y))/(∂x^2 )+(∂^2 u(t,x,y))/(∂y^2 ))+b(t)(∂u(t,x,y))/∂t+c(t)((∂u(t,x,y))/∂x+(∂u(t,x,y))/∂y) +d(t)u(t,x,y)=f(t,x,y),   (t,x,y)∈(0,T)×Ω 	(3.4)
 where Ω=(0,X)×(0,Y) for some fixed X,Y>0. The initial values are given by the initial value condition 
	u(0,x,y)=φ(x,y),    ∂u/∂t(0,x,y)=ψ(x,y),   (x,y)∈▁Ω,	(3.5)
 where ▁Ω=(0,X)×(0,Y). Since the domain Ω is bounded we require some conditions on its boundary, for example, the Dirichlet boundary condition 
	u(t,x,y)|_∂Ω=g(t,x,y),   t∈[0,T].	(3.6)

