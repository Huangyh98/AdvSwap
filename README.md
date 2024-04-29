# AdvSwap

Autonomous vehicles (AVs) are increasingly susceptible to perception module attacks, which exploit vulnerabilities in neural networks through adversarial inputs, thereby compromising AI safety. Some researches focus on creating unnoticeable adversarial samples, but existing global uniform noise techniques are detectable and difficult to deceive the human visual system (HVS). This paper introduces a novel adversarial attack framework, AdvSwap, which creatively utilizes wavelet-based high-frequency information swapping to generate stealthy adversarial examples that are difficult to detect. AdvSwap employs invertible neural network for selective high-frequency informatino exchange, preserving both forward communication and data integrity. Proposed  effectively removes original label data and incorporates guidance image data, producing concealed and robust adversarial examples. Experimental evaluations and comparations on the GTSRB and nuScenes datasets demonstrate that AdvSwap can make concealed attacks on common traffic targets, and generates adversarial samples that humans and computers are difficult to perceive. At the same time, this method also has strong attack robustness and attack transferability.

<div align="center">
	<img src="./blob/main/1_img_show.png" alt="Editor" width="500">
</div>
