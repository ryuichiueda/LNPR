# LNPR codes
completed codes of the lecture note of probabilistic robotics ("詳解確率ロボティクス" in Japanese)

## contents

### in self_localization directory

* basic methods
    * [mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/mcl.ipynb): Monte Carlo localization 
    * [kf.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/kf.ipynb): Kalman Filter
* advanced methods
    * [kld_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/kld_mcl.ipynb): MCL with KLD (Kullback–Leibler divergence) sampling
    * [adaptive_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/adaptive_mcl.ipynb): Adaptive MCL
    * [sensor_reset_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/sensor_reset_mcl.ipynb): MCL with sensor resetting
    * [expansion_reset_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/expansion_reset_mcl.ipynb): MCL with expansion resetting
    * [expansion_sensor_reset_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/expansion_sensor_reset_mcl.ipynb): MCL with sensor resetting and expansion resetting
    * [occlusion_free_mcl.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/self_localization/occlusion_free_mcl.ipynb): MCL with a non-Gaussian likelihood function

### in slam directory

* [fastslam1.0.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/slam/fastslam1.0.ipynb): FastSLAM 1.0
* [fastslam2.0.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/slam/fastslam2.0.ipynb): FastSLAM 2.0
* [graphbasedslam.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/slam/graphbasedslam.ipynb): graph-based SLAM
* misc
    * [graphbasedslam_logger.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/slam/graphbasedslam_logger.ipynb): logger for graph-based SLAM


### in mdp directory

* [dynamic_programming.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/mdp/dynamic_programming.ipynb): value iteration
* [policy_agent.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/mdp/policy_agent.ipynb): agents with the result of value iteration

### in reinforcement_learning directory

* [q.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/reinforcement_learning/q.ipynb): Q-learning
* [sarsa.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/reinforcement_learning/sarsa.ipynb): simple sarsa
* [nstep_sarsa.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/reinforcement_learning/nstep_sarsa.ipynb): n-step sarsa
* [sarsa_lambda.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/reinforcement_learning/sarsa_lambda.ipynb): sarsa($\lambda$)

### in pomdp directory

* [qmdp.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/pomdp/qmdp.ipynb): Q-MDP value method
* [pfc.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/pomdp/pfc.ipynb): weighted Q-MDP value method (probabilistic flow control)
* [amdp.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/pomdp/amdp.ipynb): value iteration with an augumented MDP (an example of corstal navigation by N. Roy in another environment and setting)
* [amdp_policy_agent.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/pomdp/amdp_policy_agent.ipynb): agents with the result of amdp

### in inference directory

* [gauss_gamma.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/inference/gauss_gamma.ipynb): Bayes inference with Gauss-gamma distribution
* [variational_inference.ipynb](https://github.com/ryuichiueda/LNPR/blob/master/inference/variational_inference.ipynb): variational inference
