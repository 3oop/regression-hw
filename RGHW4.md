# Ex 2.12

$$\beta_1 = \rho\frac{\sigma_y}{\sigma_x} \quad , \quad \beta_0 = \mu_y - \beta_1\mu_x \quad , \quad \sigma^2_{(y|x)} = \sigma^2_y(1-\rho^2)  $$

$$ \beta_1 = 0.7\sqrt{\frac{1}{3}}\quad ,\quad \beta_0 = 2 - \beta_1 2 \quad , \quad \sigma^2 = 1(1 - 0.7^2)$$

# Ex 2.14



<!-- 
$$
Q(\lambda) > 0 \Rightarrow \quad \frac{\lambda^2}{n} \sum_i^n (x_i - \bar{x})^2 + \frac{2\lambda}{n}\sum^n_i (x_i - \bar{x})(y_i - \bar{y}) + \frac{1}{n}\sum_i^n (y_i - \bar{y})^2 > 0 
$$

$$\frac{\lambda^2}{n} S_{xx} + \frac{2\lambda}{n}S_{xy} + \frac{1}{n}S_{yy} > 0 \quad \Rightarrow \quad \frac{\lambda^2}{n} S_{xx} + \frac{1}{n}S_{yy} > - \frac{2\lambda}{n}S_{xy} $$

$$\sqrt{S_{xx}S_{yy}} > 0 \quad \Rightarrow \quad \frac{\lambda^2}{n} \frac{S_{xx}} {\sqrt{S_{xx}S_{yy}}}+ \frac{1}{n}\frac{S_{yy}}{\sqrt{S_{xx}S_{yy}}} > - \frac{2\lambda}{n}r \quad \Rightarrow \quad \frac{\lambda^2}{n} \sqrt{\frac{S_{xx}}{S_{yy}}}+ \frac{1}{n}\sqrt{\frac{S_{yy}}{S_{xx}}} > - \frac{2\lambda}{n}r $$

if $\lambda > 0$
$$\lambda\sqrt{\frac{S_{xx}}{S_{yy}}}+ \frac{1}{\lambda}\sqrt{\frac{S_{yy}}{S_{xx}}} > - 2r$$

if $\lambda < 0$
$$\lambda\sqrt{\frac{S_{xx}}{S_{yy}}}+ \frac{1}{\lambda}\sqrt{\frac{S_{yy}}{S_{xx}}} < - 2r$$ -->

# Ex 3.1

(a) 
$$ y^* = \ln(y) \quad , \quad x^* = \ln(x_1 + x_2)$$

(b) No linear transform

(c) NO

(d) $$x_1 ^* = \frac{1}{x_1} \quad , \quad x_2^* = \sqrt{|x_2|}$$

(e) $$y^* = 2\ln y$$ or NO

(f) $$E[x|y] = \beta_0 + \ln \beta_1 + \ln x_1 + \beta_2 x_2 \quad \Rightarrow \quad \beta_0^* = \beta_1 + \ln\beta_1 \quad , \quad \beta_1^* = 1 \quad , \quad x_1^* = e^{x_1}$$

(g) 

(h)

# 3.12

$$ y_i = \beta_0 + \beta_1 x_i + \epsilon_i \quad , \quad \epsilon_i \sim N(0,\sigma^2x^2_i) $$

$$x^* = \frac{1}{x} \quad , \quad y^* = \frac{y}{x}$$

$$y_i^* \frac{1}{x^*_i} = \beta_0 + \beta_1 \frac{1}{x_i^*} + \epsilon_i \quad , \quad y_i^* = \beta_0 x^*_i + \beta_1 + x^*_i \epsilon_i $$

$$x^*_i \epsilon_i = \frac{\epsilon_i}{x_i} \Rightarrow Var(\frac{\epsilon_i}{x_i}) = \frac{\sigma^2 x_i^2}{x^2_i} = \sigma^2 $$

$$\epsilon_i^* = \frac{\epsilon_i}{x_i} \ \sim \ N(0 , \sigma^2)$$

$$y_i^* =  \beta_1 + \beta_0 x^*_i +\epsilon^*_i$$

Yes, and it creates a simple linear model with swaped coefficiants.
