# S2-057
S2-057 EXP 请在Python2.7下运行


## 食用说明

<pre><code>
pip install matplotlib
pip install numpy
git clone https://github.com/TheKingOfDuck/S2-057.git 
cd S2-057
python Main.pyc</code></pre>

## 影响版本
<pre>
Struts 2.3 - Struts 2.3.34
Struts 2.5 - Struts 2.5.16
</pre>
## 修复建议
<pre>
1.升级到Struts 2.3.35或Struts 2.5.17

2.临时解决方案:
验证您是否已namespace为基础xml配置中的所有已定义结果设置（并且始终不会忘记设置）（如果适用）。还要验证您是否已设置（并且始终不会忘记设置）value或JSP中的action所有url标记。仅当它们的上部动作配置没有或通配符时才需要它们namespace。
</pre>
