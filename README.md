#### OpenMM 教程环境配置与软件安装

1. 下载并安装miniconda：https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html

2. 将conda-forge添加至频道中：

   ```bash
   conda config --add channels conda-forge
   ```

3. 创建装有所需软件包的conda环境：

   ```bash
   conda create -n tutorial openmm numpy matplotlib nglview MDAnalysis
   ```

4.  激活虚拟环境：

   ```
   conda activate tutorial
   ```

5. 安装jupyter notebook:

   ```bash
   pip3 install notebook
   ```

6. 运行教程notebook：

   ```bash
   jupyter notebook OpenMM_tutorial_mingyuanzhang.ipynb
   ```

7. 跟随notebook中的流程即可