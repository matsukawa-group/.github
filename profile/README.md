# 明治大学理工学部機械工学科 流体力学研究室（中研究室）松川班

[明治大学](https://www.meiji.ac.jp/) [理工学部](https://www.meiji.ac.jp/sst/) [機械工学科](https://www.meiji.ac.jp/sst/mech/index.html) [流体力学研究室（中研究室）](https://www.isc.meiji.ac.jp/~naka/)助教の [松川裕樹](https://yuki-matsukawa.github.io/index-j.html) が管理する GitHub Organization です．

## 研究内容

流体力学研究室は流体力学の中でも乱流現象の物理・計測の研究を行っていますが，松川は学生時代から乱流遷移の数値シミュレーションを研究対象としています．
特に，複数の主流が直交する複合剪断流における超臨界・亜臨界乱流遷移現象および伝熱特性の研究を行っています．

層流から乱流または乱流から層流に向けての中間として遷移域が存在し，その遷移過程には超臨界遷移と亜臨界遷移の二種類が存在します<sup>[1]</sup>．
超臨界遷移は，Reynolds 数が上昇し線形（局所）安定臨界 Reynolds 数 $Re_L$ を超えると基本流が線形不安定となり，その後段階的に流れ場が複雑化して乱流に至る遷移過程です．Rayleigh–Bénard 対流などの熱対流系や内円筒回転のみの Taylor–Couette 流などに見られます．
一方の亜臨界遷移は $Re_G$ 以下であっても，突発的な乱流遷移を引き起こす遷移過程です．
例えば，Reynolds の実験<sup>[2]</sup>に代表されるような円管内流れは線形安定性解析で $Re_L \to \infty$ となりますが，これは我々の直観に反した結果です．
実際には $Re \approx 2000$（大抵はこれより大きい Reynolds 数）で乱流に遷移します．
線形安定性理論では線形撹乱（無限小撹乱）に対しての基本流の安定性を調べていますが，実際の流体現象と対応させるには撹乱の非線形性を考慮した有限小撹乱に対しての非線形安定性を調べる必要があります．
したがって，亜臨界遷移域は「線形安定だが非線形不安定となりうる領域」であるため，理論的アプローチが難しい問題となります．
壁面剪断流の多くは亜臨界遷移に属し，乱流維持下限の大域的安定臨界 Reynolds 数 $Re_G$ 近傍では層流と乱流が時空間的に共存し，局在化した乱流が乱流パフ<sup>[2]</sup>や乱流縞<sup>[3,4]</sup>と呼ばれる特徴的なパターンを形成します．
私はこれらの超・亜臨界遷移現象の解明を目指し，大規模な直接数値計算を実施しています．

### 参考文献

1. P. Manneville, "Transition to turbulence in wall-bounded flows: Where do we stand?," [*Mechanical Engineering Reviews*](https://www.jstage.jst.go.jp/browse/mer), **3**(2) (2016), 15-00684. [[Web Page](https://www.jstage.jst.go.jp/article/mer/3/2/3_15-00684/_article) (Open Access)]
2. O. Reynolds, "An experimental investigation of the circumstances which determine whether the motion of water shall be direct or sinuous, and of the law of resistance in parallel channels," [*Philosophical Transactions of the Royal Society*](https://royalsocietypublishing.org/journal/rstl), **174** (1883), 935–982. [[Web Page](https://doi.org/10.1098/rstl.1883.0029) (Open Access)]
3. T. Tsukahara, Y. Seki, H. Kawamura and D. Tochio, "DNS of turbulent channel flow at very low Reynolds numbers," *Proceedings of 4th International Symposium on Turbulence and Shear Flow Phenomena* (2005), 935–940. [[Web Page](https://doi.org/10.1615/TSFP4.1550)]
4. A. Prigent, G. Grégoire, H. Chaté, O. Dauchot and W. van Saarloos, "Large-scale finite-wavelength modulation within turbulent shear flows," [*Physical Review Letters*](https://journals.aps.org/prl/), **89** (2002), 014501. [[Web Page](https://doi.org/10.1103/PhysRevLett.89.014501)]

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
