We generate the square patch on 2000 randomly selected pictures with 50 epochs and 6% noise. The shape of the patch is (54, 54, 3). And the generated patch is tested on 1000 rondomly selected pictures. The attack success rate on the testset of our best adversarial patch is 99.61% and it's generated at 46th epoch. 
Note that the accuracy of the ResNet50 on clean trainset and clean testset is 68.500% and 74.600%. 
## best patch
![best_patch](./pictures/best_patch.png)
## training line
![training line](./pictures/patch_attack_success_rate.png)
