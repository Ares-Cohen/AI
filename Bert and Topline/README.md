任务二是使用 Bert/Topline 方法，通过对论文摘要等信息的理解，判断该论文是否属于医学领域的文献。

任务示例：

输入：

论文信息，格式如下：

Inflammatory Breast Cancer: What to Know About This Unique, Aggressive Breast Cancer.，

[Arjun Menta, Tamer M Fouad, Anthony Lucci, Huong Le-Petross, Michael C Stauder, Wendy A Woodward, Naoto T Ueno, Bora Lim]，

Inflammatory breast cancer (IBC) is a rare form of breast cancer that accounts for only 2% to 4% of all breast cancer cases. Despite its low incidence, IBC contributes to 7% to 10% of breast cancer caused mortality. Despite ongoing international efforts to formulate better diagnosis, treatment, and research, the survival of patients with IBC has not been significantly improved, and there are no therapeutic agents that specifically target IBC to date. The authors present a comprehensive overview that aims to assess the present and new management strategies of IBC.，

Breast changes; Clinical trials; Inflammatory breast cancer; Trimodality care.

输出：

是(1)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

for_paper_classification -> Topline

Bert -> Bert

Topline and Bert.ipynb 为 Topline.ipynb 与 Bert.ipynb 合并后的笔记
