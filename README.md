# GPU-CPU Memory Transfer

## Authors
- Alonzo, Jose Anton
- Avelino, Joris Gabriel
- Cruz, Airon John
- Hernandez, Pierre Vincent

## About the project
CPU and GPU are two separate processors; each has its memory. There are several ways in
which data are transferred between processors, as follows:
- Unified memory introduced in CUDA 6
- Prefetching of data with memory advice
- Data transfer or initialization as a CUDA kernel
- Old method of transferring data between CPU and memory (memCUDA copy)

Discuss:
- Explain the concepts of each method and how it is implemented
- Compare (a) the execution time of the kernel as well as (b) the memory transfer time
(taking into consideration page faults, overhead time if it’s a separate transfer time, or
part of the kernel transfer time already).

## Important Links
- YouTube video presentation: [https://youtu.be/pRprKLqauH4](https://youtu.be/pRprKLqauH4)
- Google Colab link [View access only]: [https://colab.research.google.com/drive/1fouudeoADH6v3W_3lIBvbTXAjzG6wS0_?usp=sharing](https://colab.research.google.com/drive/1fouudeoADH6v3W_3lIBvbTXAjzG6wS0_?usp=sharing)
    - NOTE: Must be a part of the DLSU organzation when accessing the Google Colab link
