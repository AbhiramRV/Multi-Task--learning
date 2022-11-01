# Multi-Task--learning

Multi task learning is the task of using single network to do perform multiple task like Image detection, semantic-segmentation and depth estimation instead of using multiple networks which preform only one specific task.

These kinds of neural networks are also called HydraNets.

Hydra nets have common back bone and many heads. Tesla is using these kinds of networks for perception task in achieving full self driving.

These kind of networks have common encoder stage(i.e feature extraction stage). But in decoding stage, multiple heads are present to perform multiple tasks.

Link for a very good medium article explaining the entire perception stack of tesla full self driving.
https://saneryee-studio.medium.com/deep-understanding-tesla-fsd-part-1-hydranet-1b46106d57

