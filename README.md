We propose a multi-agent Q-learning algorithm 𝚅𝚁𝙳𝚀 for static and time-varying networks, which achieves provable collaborative speedups in sample complexity. The method combines two complementary ingredients: (i) operator refinement via batched updates and (ii) streamlined diffusion of updates among neighbors within each batch. These components are decoupled by design, isolating their effects and enabling a simplified finite-time analysis. Notably, the algorithm uses only logarithmic communication rounds, substantially lowering the communication overhead. Although developed for Q-learning, the framework extends naturally to broader reinforcement-learning settings, highlighting its generality and practicality.
<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Q-Learning-over-Static-and-Time-Varying-Networks/blob/main/Figures/combined_network_error.gif" style="width:800px">
 </td>
</tr>
<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Robust-Federated-Q-Learning-with-Almost-No-communication/blob/main/Figures%20Robust%20Fed-Q/Figure%201%20Robust%20Fed%20Q%20with%20corruption%20fraction%200.01.png" style="width:390px">
    <img src="https://github.com/sreejeetm1729/Robust-Federated-Q-Learning-with-Almost-No-communication/blob/main/Figures%20Robust%20Fed-Q/Figure%202%20Robust%20Fed%20Q%20with%20corruption%20fraction%200.01.png" style="width:390px">
 </td>
</tr>
