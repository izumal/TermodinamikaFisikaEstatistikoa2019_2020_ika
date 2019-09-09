
$z \equiv \exp (\mu / k T)$  

$a(\varepsilon) d \varepsilon=\left(2 \pi V / h^{3}\right)(2 m)^{3 / 2} \varepsilon^{1 / 2} d \varepsilon$  

$\lambda_{T}[\lambda]\equiv\frac{h }{\sqrt{2 \pi m k T}}$  




bosoiak: $\frac{P V}{k T}=\ln \mathcal{Q}=-\sum\limits_{\varepsilon} \ln \left(1-z e^{-\beta t}\right)$  

fermioiak: $\frac{P V}{k T}=\ln \mathcal{Q}=\sum\limits_{\varepsilon} \ln \left(1+z e^{-\beta t}\right)$  

################# Blundell

$\mathcal{Z}=\prod_{\boldsymbol{k}} \mathcal{Z}_{k}^{2 S+1}$  

$\mathcal{Z}_{k}=\left(1 \pm \mathrm{e}^{-\beta\left(E_{k}-\mu\right)}\right)^{ \pm 1}$  

###################  



$\begin{aligned} \Phi_{\mathrm{G}} &=-k_{\mathrm{B}} T \ln \mathcal{Z} \\ &=\mp k_{\mathrm{B}} T(2 S+1) \sum_{k} \ln \left(1 \pm \mathrm{e}^{-\beta\left(E_{k}-\mu\right)}\right) \\ &=\mp k_{\mathrm{B}} T(2 S+1) \int_{0}^{\infty} \ln \left(1 \pm \mathrm{e}^{-\beta(E-\mu)}\right) g(E) \mathrm{d} E \end{aligned}$

$g(k) \mathrm{d} k=\frac{4 \pi k^{2} \mathrm{d} k}{(2 \pi / L)^{3}} \times(2 S+1)=\frac{(2 S+1) V k^{2} \mathrm{d} k}{2 \pi^{2}}$  

$E=\frac{\hbar^{2} k^{2}}{2 m}$  

$g(E) \mathrm{d} E=\frac{(2 S+1) V E^{1 / 2} \mathrm{d} E}{(2 \pi)^{2}}\left(\frac{2 m}{\hbar^{2}}\right)^{3/2}$  

$\Phi_{\mathrm{G}}=\mp k_{\mathrm{B}} T \frac{(2 S+1) V}{(2 \pi)^{2}}\left(\frac{2 m}{\hbar^{2}}\right)^{3 / 2} \int_{0}^{\infty} \ln \left(1 \pm \mathrm{e}^{-\beta(E-\mu)}\right) E^{1 / 2} \mathrm{d} E$  

$n_{k}=k_{\mathrm{B}} T \frac{\partial}{\partial \mu} \mathcal{Z}_{k}=\frac{1}{\mathrm{e}^{\beta\left(E_{k}-\mu\right)} \pm 1}$  

$N=\sum_{k} n_{k}=\int_{0}^{\infty} \frac{g(E) \mathrm{d} E}{\mathrm{e}^{\beta\left(E_{k}-\mu\right)} \pm 1}$  

$U=\sum_{\boldsymbol{k}} n_{k} E_{k}=\int_{0}^{\infty} \frac{E g(E) \mathrm{d} E}{\mathrm{e}^{\beta\left(E_{k}-\mu\right)} \pm 1}$  

$$\begin{aligned} N &=\left[\frac{(2 S+1) V}{(2 \pi)^{2}}\left(\frac{2 m}{\hbar^{2}}\right)^{3 / 2}\right] \int_{0}^{\infty} \frac{E^{1 / 2} \mathrm{d} E}{z^{-1} \mathrm{e}^{\beta E} \pm 1} \\ U &=\left[\frac{(2 S+1) V}{(2 \pi)^{2}}\left(\frac{2 m}{\hbar^{2}}\right)^{3 / 2}\right] \int_{0}^{\infty} \frac{E^{3 / 2} \mathrm{d} E}{z^{-1} \mathrm{e}^{\beta E} \pm 1} \end{aligned}$$  

$\int_{0}^{\infty} \frac{E^{n-1} \mathrm{d} E}{z^{-1} \mathrm{e}^{\beta E} \pm 1}=\left(k_{\mathrm{B}} T\right)^{n} \Gamma(n)\left[\mp \mathrm{Li}_{n}(\mp z)\right]$  

$N=\frac{(2 S+1) V}{\lambda_{\mathrm{th}}^{3}}\left[\mp \mathrm{Li}_{3 / 2}(\mp z)\right]$  

$\begin{aligned} U &=\frac{3}{2} k_{\mathrm{B}} T \frac{(2 S+1) V}{\lambda_{\mathrm{th}}^{3}}\left[\mp \mathrm{Li}_{5 / 2}(\mp z)\right] \\ &=\frac{3}{2} N k_{\mathrm{B}} T \frac{\mathrm{Li}_{5 / 2}(\mp z)}{\mathrm{Li}_{3 / 2}(\mp z)} \end{aligned}$  

#####################

bosoiak: $g_{v}(z)=\frac{1}{\Gamma(v)} \int_{0}^{\infty} \frac{x^{v-1} d x}{z^{-1} e^{x}-1}=z+\frac{z^{2}}{2^{v}}+\frac{z^{3}}{3^{v}}+\cdots$  

fermioiak: $f_{v}(z)=\frac{1}{\Gamma(v)} \int_{0}^{\infty} \frac{x^{\nu-1} d x}{z^{-1} e^{x}+1}=z-\frac{z^{2}}{2^{v}}+\frac{z^{3}}{3^{v}}-\dots$


bosoiak: $N \equiv \sum\limits_{\varepsilon}\left\langle n_{\varepsilon}\right\rangle=\sum\limits_{\varepsilon} \frac{1}{z^{-1} e^{\beta \varepsilon}-1}$  

fermioiak: $N \equiv \sum\limits_{\varepsilon}\left\langle n_{\varepsilon}\right\rangle=\sum\limits_{\varepsilon} \frac{1}{z^{-1} e^{\beta \varepsilon}+1}$  

########

- Bosoiak: 

$\frac{P}{k T}=-\frac{2 \pi}{h^{3}}(2 m)^{3 / 2} \int_{0}^{\infty} \varepsilon^{1 / 2} \ln \left(1-z e^{-\beta \varepsilon}\right) d \varepsilon-\frac{1}{V} \ln (1-z)$  

$\frac{N}{V}=\frac{2 \pi}{h^{3}}(2 m)^{3 / 2} \int_{0}^{\infty} \frac{\varepsilon^{1 / 2} d \varepsilon}{z^{-1} e^{\beta \varepsilon}-1}+\frac{1}{V} \frac{z}{1-z}$  


$\frac{P}{k T}=-\frac{2 \pi(2 m k T)^{3 / 2}}{h^{3}} \int_{0}^{\infty} x^{1 / 2} \ln \left(1-z e^{-x}\right) d x=\frac{1}{\lambda^{3}} g_{5 / 2}(z)$  

$\frac{N-N_{0}}{V}=\frac{2 \pi(2 m k T)^{3 / 2}}{h^{3}} \int_{0}^{\infty} \frac{x^{1 / 2} d x}{z^{-1} e^{x}-1}=\frac{1}{\lambda^{3}} g_{3 / 2}(z)$  



$\begin{aligned} U & \equiv-\left(\frac{\partial}{\partial \beta} \ln \mathcal{Q}\right)_{z, V}=k T^{2}\left\{\frac{\partial}{\partial T}\left(\frac{P V}{k T}\right)\right\}_{z, V} \\ &=k T^{2} V g_{5 / 2}(z)\left\{\frac{d}{d T}\left(\frac{1}{\lambda^{3}}\right)\right\}=\frac{3}{2} k T \frac{V}{\lambda^{3}} g_{5 / 2}(z) \end{aligned}$  

$\frac{P V}{N k T}=\sum\limits_{l=1}^{\infty} a_{l}\left(\frac{\lambda^{3}}{v}\right)^{l-1}$  

$\left.\begin{aligned} a_{1} &=1 \\ a_{2} &=-\frac{1}{4 \sqrt{2}}=-0.17678 \\ a_{3} &=-\left(\frac{2}{9 \sqrt{3}}-\frac{1}{8}\right)=-0.00330 \\ a_{4} &=-\left(\frac{3}{32}+\frac{5}{32 \sqrt{2}}-\frac{1}{2 \sqrt{6}}\right)=-0.00011 \end{aligned}\right\}$  

$\begin{aligned} \frac{C_{V}}{N k} & \equiv \frac{1}{N k}\left(\frac{\partial U}{\partial T}\right)_{N, V}=\frac{3}{2}\left\{\frac{\partial}{\partial T}\left(\frac{P V}{N k}\right)\right\}_{v} \\ &=\frac{3}{2} \sum_{l=1}^{\infty} \frac{5-3 l}{2} a_{l}\left(\frac{\lambda^{3}}{v}\right)^{l-1} \\ &=\frac{3}{2}\left[1+0.0884\left(\frac{\lambda^{3}}{v}\right)+0.0066\left(\frac{\lambda^{3}}{v}\right)^{2}+0.0004\left(\frac{\lambda^{3}}{v}\right)^{3}+\cdots\right] \end{aligned}$  

$N_{e}=V \frac{(2 \pi m k T)^{3 / 2}}{h^{3}} g_{3 / 2}(z)$  

$g_{3 / 2}(1)=1+\frac{1}{2^{3 / 2}}+\frac{1}{3^{3 / 2}}+\cdots \equiv \mathcal{\xi}\left(\frac{3}{2}\right) \simeq 2.612$  

$g_{3/2}(z) \leq \zeta\left(\frac{3}{2}\right)$  

$N_{e} \leq V \frac{(2 \pi m k T)^{3 / 2}}{h^{3}} \zeta\left(\frac{3}{2}\right)$  


$N_{e}=V \frac{(2 \pi m k T)^{3 / 2}}{h^{3}} \zeta\left(\frac{3}{2}\right)$  

$N_{0}=N-\left\{V \frac{(2 \pi m k T)^{3 / 2}}{h^{3}} \zeta\left(\frac{3}{2}\right)\right\}$  


$z=\frac{N_{0}}{N_{0}+1} \simeq 1-\frac{1}{N_{0}}$  

$N>V T^{3 / 2} \frac{(2 \pi m k)^{3 / 2}}{h^{3}} \zeta\left(\frac{3}{2}\right)$  


$T<T_{c}=\frac{h^{2}}{2 \pi m k}\left\{\frac{N}{V \zeta\left(\frac{3}{2}\right)}\right\}^{2 / 3}$  

$$  


$$  

$$  


$$  

$$  


