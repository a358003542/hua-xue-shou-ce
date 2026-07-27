## 有机化合物pubchem对接演示文档

测试中...

本测试文本试图从markdown中建立一套合理的化学物质嵌入方案。

初步定调markdown本地渲染方案不合适，markdown本来定为就是简洁的文本编辑，所以必须实现markdown的化合物轻量文本记录和后续渲染服务支持。


### vscode推荐安装插件
推荐安装 [molview插件](https://marketplace.visualstudio.com/items?itemName=milicam.smiles-renderer) 

这样SMILES字符串可以直接弹出化合物2d图形结构式。




- 水  O

- 咖啡因 CN1C=NC2=C1C(=O)N(C(=O)N2C)C

- 阿司匹林 CC(=O)Oc1ccccc1C(=O)O

- 青霉素  CC1(C(N2C(S1)C(C2=O)NC(=O)Cc3ccccc3)C(=O)O)C

食盐

$\mathrm{NaCl}$ 

胆矾


CuSO4·5H2O

$\mathrm{CuSO_4\cdot5H_2O}$

C9H8O4

CN1C=NC2=C1C(=O)N(C(=O)N2C)C

[CC(=O)Oc1ccccc1C(=O)O](https://pubchem.ncbi.nlm.nih.gov/#query=CC(=O)Oc1ccccc1C(=O)O)

![CC(=O)Oc1ccccc1C(=O)O](https://cactus.nci.nih.gov/chemical/structure/CC(=O)Oc1ccccc1C(=O)O/image)


| 化合物 | SMILES / 标识 | 2D 预览 (内嵌)  |
| :--- | :--- | :---  |
| **水** | `O` | ![O](https://cactus.nci.nih.gov/chemical/structure/O/image)  |
| **咖啡因** | `CN1C=NC2=C1C(=O)N(C(=O)N2C)C` | ![CN1C=NC2=C1C(=O)N(C(=O)N2C)C](https://cactus.nci.nih.gov/chemical/structure/CN1C=NC2=C1C(=O)N(C(=O)N2C)C/image) |
| **阿司匹林** | `CC(=O)Oc1ccccc1C(=O)O` | ![CC(=O)Oc1ccccc1C(=O)O](https://cactus.nci.nih.gov/chemical/structure/CC(=O)Oc1ccccc1C(=O)O/image) |
| **青霉素** | `CC1(C(N2C(S1)C(C2=O)NC(=O)Cc3ccccc3)C(=O)O)C` | ![CC1(C(N2C(S1)C(C2=O)NC(=O)Cc3ccccc3)C(=O)O)C](https://cactus.nci.nih.gov/chemical/structure/CC1(C(N2C(S1)C(C2=O)NC(=O)Cc3ccccc3)C(=O)O)C/image) |
