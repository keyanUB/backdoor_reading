## Target Backdoor Attacks on Deep Learning System using Data Poisoning [pdf](https://arxiv.org/pdf/1712.05526.pdf)

### Introduction
- Attacker: Create a backdoor into a learning-based authentication system
- Backdoor Poisoning Attack -target attack
- Weak and realistic model:
    * attacker has no knowledge of the victim model or its training data
    * attacker can inject only a small number of poisoning samples into training data
- 2 poisoning strategies:</br>
    1> attacker injects few poisoning sample</br>
    2> attacker create a wide range of backdoor instances
    
### Thread Model
- Black-box poisoning
- Unawareness of training data
- Tageted attacks: </br>
   any back door instances will be classified as a target lable; </br> the overall performance of learning system will not be affected.
- Limited injection valume
- Stealthiness of the backdoor key
- Physical attack

### Backdoor Poisoning Attacks
- Traditional backdoor:<br/>
   A traditional backdoor in an operating system or an application refers to a piece of malicious code embedded by an attacker into such systems, which can enable the attacker to obtain higher privilege than otherwise allowed, such as by authenticating through a particular password of the attacker’s choice.
   * Machine Learning
