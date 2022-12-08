# resnet_class_cifar10
下载直接使用即可，可以自己增加权重保存 、
path = 'weight/cifar_resnet.pth'
torch.save(model.state_dict(),path)#加到循环里面去 epoch可以设置为10提高训练准确率。
