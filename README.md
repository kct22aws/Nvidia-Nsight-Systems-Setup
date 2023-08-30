# Nvidia Nsight Systems in AWS EC2 GPU instance

## Summary

The purpose of this document is to show how to run [Nvidia Nsight Systems](https://developer.nvidia.com/nsight-systems) from your local desktop to profile an EC2 GPU (i.e., g4dn.xl) instance’s performance. In order to make this work, you have to enable password login in the EC2, so Nsight can connect via SSH to the EC2 instance . Also, Nsight needs to have permission to access the GPU’s performance counters on the targeted device in the EC2 instance. This documentation provides instructions to the set up.

