###IMP-ucasthesis 使用说明
==========

LaTeX thesis template for The Institute of Modern Physics (IMP), Chinese Academy of Sciences 中国科学院近代物理研究所学位论文模板
 
由于近物所的特殊要求，于是对国科大模板进行了多次修改，目前此模板论文已通过所里审核，大家放心使用。

在此感谢所有为科学院学位论文模板贡献代码的师兄师姐以及所有反馈问题的同学们。

此中国科学院大学学位论文模板 ucasthesis 基于吴凌云的 CASthesis 模板发展而来，ucasthesis 文档类的基础架构为 ctexbook 文档类。当前 ucasthesis 模板满足最新的中国科学院大学学位论文撰写要求和封面设定。模板兼顾不同操作系统 (Windows, Linux, Mac OS) 并兼容 pdflatex 和 xelatex 编译方式，完美地支持中文书签、中文渲染、中文粗体显示、拷贝 pdf 中的文本到其他文本编辑器等特性，此外，对模板的文档结构进行了精心设计，撰写了编译脚本提高模板的易用性和使用效率。

宏包的目的是简化学位论文的撰写，模板文档的默认设定是十分规范的，从而论文作者可以将精力集中到论文的内容上，而不需要在版面设置上花费精力。 同时，在编写模板的 LaTeX 文档代码过程中，作者对各结构和命令进行了十分详细的注解，并提供了整洁一致的代码结构，对文档的仔细阅读可以为初学的您提供一个学习 LaTeX 的窗口。除此之外，整个模板的架构十分注重通用性，事实上，本模板不仅是中国科学院大学学文论文模板，同时，也是使用 LaTeX 撰写中英文 article 或 book 的通用模板，并为使用者的个性化设定提供了接口和相应的代码。

具体使用细节请见下载附件中的 UCASthesis Documentation "HowToUse.pdf"。

###Change log:
==========

2017-06-12 在原来ucasthesis基础上修改符合IMP的模板 
==========
2017-06-12 在原来ucasthesis基础上修改符合IMP的模板 

2017-05-14 将文献上标引用设定为默认，增加 \citepns{} 和 \citetns{} 命令提供嵌入式非上标引用以满足有混合引用需要的用户，问题/建议由赵永明同学提出。修改的文件为：custom.sty，commons.sty。

2017-05-14 对用户文档 HowToUse.pdf 进行了扩充，回答用户常见问题。修改的文件为：HowToUse.pdf。

2017-05-14 从 zepinglee/gbt-7714-2015 更新国标的参考文献样式文件。修改的文件为：gbt-7714-2015-numerical，gbt-7714-2015-author-year。

2017-03-08 在 Frontpage.tex 中添加一个设定论文类型为 thesis 或 dissertation 的命令 \englishthesistype{}，问题/建议由臧光明同学提出。修改的文件为：ucasthesis.cls，Frontpage.tex。

2016-10-02 添加 中国科学院大学开题报告 LaTeX 模板 https://github.com/mohuangrui/ucasproposal。

2016-05-28 缩减章节标题的空隙。修改的文件为：ucasthesis.cfg。

2016-05-24 在目录中添加点断线。修改的文件为：ucasthesis.cls。

2016-04-25 从 xiaoyao9933/UCASthesis 引入 PDF 版的 国科大 Logo，从 zepinglee/gbt-7714-2015 引入符合国标的参考文献样式文件。修改的文件为：ucas.pdf，gbt-7714-2015-numerical，gbt-7714-2015-author-year。

2016-04-03 修改模板可直接在Tex编辑器 (如 WinEdit，Texmaker) 中编译。修改的文件为：Thesis.tex，Main_Content.tex。

2016-03-29 修正封面下划线的颜色为黑色。修改的文件为：ucasthesis.cls。

2016-03-18 修正图列表和表格列表的页码链接。修改的文件为：custom.sty，Thesis.tex 。
