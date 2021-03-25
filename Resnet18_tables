
The Resnet18 Retinanet architecture used in the experiments is depicted bellow.

\begin{table}[tb]
\centering
\begin{tabular}{|l|l|}
\multicolumn{1}{c}{\textbf{name}} & \multicolumn{1}{c}{\textbf{\#elements or shape}} \\
model & 19.8M \\
backbone & 14.9M \\
backbone.fpn\_lateral3 & 33.0K \\
backbone.fpn\_lateral3.weight & (256, 128, 1, 1) \\
backbone.fpn\_lateral3.bias & (256,) \\
backbone.fpn\_output3 & 0.6M \\
backbone.fpn\_output3.weight & (256, 256, 3, 3) \\
backbone.fpn\_output3.bias & (256,) \\
backbone.fpn\_lateral4 & 65.8K \\
backbone.fpn\_lateral4.weight & (256, 256, 1, 1) \\
backbone.fpn\_lateral4.bias & (256,) \\
backbone.fpn\_output4 & 0.6M \\
backbone.fpn\_output4.weight & (256, 256, 3, 3) \\
backbone.fpn\_output4.bias & (256,) \\
backbone.fpn\_lateral5 & 0.1M \\
backbone.fpn\_lateral5.weight & (256, 512, 1, 1) \\
backbone.fpn\_lateral5.bias & (256,) \\
backbone.fpn\_output5 & 0.6M \\
backbone.fpn\_output5.weight & (256, 256, 3, 3) \\
backbone.fpn\_output5.bias & (256,) \\
backbone.top\_block & 1.8M \\
backbone.top\_block.p6 & 1.2M \\
backbone.top\_block.p7 & 0.6M \\
backbone.bottom\_up & 11.2M \\
backbone.bottom\_up.stem & 9.4K \\
backbone.bottom\_up.res2 & 0.1M \\
backbone.bottom\_up.res3 & 0.5M \\
backbone.bottom\_up.res4 & 2.1M \\
backbone.bottom\_up.res5 & 8.4M \\
head & 4.9M \\
head.cls\_subnet & 2.4M \\
head.cls\_subnet.0 & 0.6M \\
head.cls\_subnet.2 & 0.6M \\
head.cls\_subnet.4 & 0.6M \\
head.cls\_subnet.6 & 0.6M \\
head.bbox\_subnet & 2.4M \\
head.bbox\_subnet.0 & 0.6M \\
head.bbox\_subnet.2 & 0.6M \\
head.bbox\_subnet.4 & 0.6M \\
head.bbox\_subnet.6 & 0.6M \\
head.cls\_score & 83.0K \\
head.cls\_score.weight & (36, 256, 3, 3) \\
head.cls\_score.bias & (36,) \\
head.bbox\_pred & 83.0K \\
head.bbox\_pred.weight & (36, 256, 3, 3) \\
head.bbox\_pred.bias & (36,)
\end{tabular}
\caption{Architecture details of the Resnet18 Retinanet model used in Urpc and Brackish. Model available on Detectron2.}\label{tab:res18_ret}
\end{table}


The Resnet18 Faster RCNN architecture is depicted in table bellow.

\begin{table}[tb]
\centering
\begin{tabular}{|l|l|}
\multicolumn{1}{c}{\textbf{name}} & \multicolumn{1}{c}{\textbf{\#elements or shape}} \\
model & 28.3M \\
backbone & 13.8M \\
backbone.fpn\_lateral2 & 16.6K \\
backbone.fpn\_lateral2.weight & (256, 64, 1, 1) \\
backbone.fpn\_lateral2.bias & (256,) \\
backbone.fpn\_output2 & 0.6M \\
backbone.fpn\_output2.weight & (256, 256, 3, 3) \\
backbone.fpn\_output2.bias & (256,) \\
backbone.fpn\_lateral3 & 33.0K \\
backbone.fpn\_lateral3.weight & (256, 128, 1, 1) \\
backbone.fpn\_lateral3.bias & (256,) \\
backbone.fpn\_output3 & 0.6M \\
backbone.fpn\_output3.weight & (256, 256, 3, 3) \\
backbone.fpn\_output3.bias & (256,) \\
backbone.fpn\_lateral4 & 65.8K \\
backbone.fpn\_lateral4.weight & (256, 256, 1, 1) \\
backbone.fpn\_lateral4.bias & (256,) \\
backbone.fpn\_output4 & 0.6M \\
backbone.fpn\_output4.weight & (256, 256, 3, 3) \\
backbone.fpn\_output4.bias & (256,) \\
backbone.fpn\_lateral5 & 0.1M \\
backbone.fpn\_lateral5.weight & (256, 512, 1, 1) \\
backbone.fpn\_lateral5.bias & (256,) \\
backbone.fpn\_output5 & 0.6M \\
backbone.fpn\_output5.weight & (256, 256, 3, 3) \\
backbone.fpn\_output5.bias & (256,) \\
backbone.bottom\_up & 11.2M \\
backbone.bottom\_up.stem & 9.4K \\
backbone.bottom\_up.res2 & 0.1M \\
backbone.bottom\_up.res3 & 0.5M \\
backbone.bottom\_up.res4 & 2.1M \\
backbone.bottom\_up.res5 & 8.4M \\
proposal\_generator & 0.6M \\
proposal\_generator.rpn\_head & 0.6M \\
proposal\_generator.rpn\_head.conv & 0.6M \\
proposal\_generator.rpn\_head.objectness\_logits & 0.8K \\
proposal\_generator.rpn\_head.anchor\_deltas & 3.1K \\
roi\_heads & 13.9M \\
roi\_heads.box\_head & 13.9M \\
roi\_heads.box\_head.fc1 & 12.8M \\
roi\_heads.box\_head.fc2 & 1.0M \\
roi\_heads.box\_predictor & 21.5K \\
roi\_heads.box\_predictor.cls\_score & 5.1K \\
roi\_heads.box\_predictor.bbox\_pred & 16.4K
\end{tabular}
\caption{Architecture details of the Resnet18 Faster RCNN model used in Urpc and Brackish. Model available on Detectron2.}\label{tab:res18_fas}
\end{table}
