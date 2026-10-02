# 明治大学理工学部機械工学科 流体力学研究室（中研究室）松川班

[明治大学](https://www.meiji.ac.jp/) [理工学部](https://www.meiji.ac.jp/sst/) [機械工学科](https://www.meiji.ac.jp/sst/mech/index.html) [流体力学研究室（中研究室）](https://www.isc.meiji.ac.jp/~naka/)助教の [松川裕樹](https://yuki-matsukawa.github.io/index-j.html) が管理する GitHub Organization です．
研究内容の紹介と，公開しているリポジトリをまとめています．

## 🔬 研究内容

流体力学研究室は流体力学の中でも乱流現象の物理・計測の研究を行っていますが，松川は学生時代から乱流遷移の数値シミュレーションを研究対象としています．
特に，複数の主流が直交する複合剪断流における超臨界・亜臨界乱流遷移現象および伝熱特性の研究を行っています．

層流から乱流または乱流から層流に向けての中間として遷移域が存在し，その遷移過程には超臨界遷移と亜臨界遷移の二種類が存在します<sup>[1]</sup>．
超臨界遷移は，Reynolds 数が上昇し線形（局所）安定臨界 Reynolds 数 $Re_L$ を超えると基本流が線形不安定となり，その後段階的に流れ場が複雑化して乱流に至る遷移過程です．
Rayleigh–Bénard 対流などの熱対流系や内円筒回転のみの Taylor–Couette 流などに見られます．

一方の亜臨界遷移は $Re_L$ 以下であっても，突発的な乱流遷移を引き起こす遷移過程です．
例えば，Reynolds の実験<sup>[2]</sup>に代表されるような円管内流れは線形安定性解析で $Re_L \to \infty$ となりますが，これは我々の直観に反した結果です．
実際には $Re \approx 2000$（大抵はこれより大きい Reynolds 数）で乱流に遷移します．
線形安定性理論では線形撹乱（無限小撹乱）に対しての基本流の安定性を調べていますが，実際の流体現象と対応させるには撹乱の非線形性を考慮した有限小撹乱に対しての非線形安定性を調べる必要があります．
したがって，亜臨界遷移域は「線形安定だが非線形不安定となりうる領域」であるため，理論的アプローチが難しい問題となります．
壁面剪断流の多くは亜臨界遷移に属し，乱流維持下限の大域的安定臨界 Reynolds 数 $Re_G$ 近傍では層流と乱流が時空間的に共存し，局在化した乱流が乱流パフ<sup>[3]</sup>や乱流縞<sup>[4,5]</sup>と呼ばれる特徴的なパターンを形成します．
松川はこれらの超・亜臨界遷移現象の解明を目指し，大規模な直接数値計算を実施しています．

### 参考文献

1. P. Manneville, "Transition to turbulence in wall-bounded flows: Where do we stand?," [*Mechanical Engineering Reviews*](https://www.jstage.jst.go.jp/browse/mer), **3**(2) (2016), 15-00684. [[Web Page](https://www.jstage.jst.go.jp/article/mer/3/2/3_15-00684/_article) (Open Access)]
2. O. Reynolds, "An experimental investigation of the circumstances which determine whether the motion of water shall be direct or sinuous, and of the law of resistance in parallel channels," [*Philosophical Transactions of the Royal Society*](https://royalsocietypublishing.org/journal/rstl), **174** (1883), 935–982. [[Web Page](https://doi.org/10.1098/rstl.1883.0029) (Open Access)]
3. I. J. Wygnanski and F. H. Champagne, "On transition in a pipe. Part 1. The origin of puffs and slugs and the flow in a turbulent slug," [*Journal of Fluid Mechanics*](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics), **59**(2) (1973), 281–335. [[Web Page](https://doi.org/10.1017/S0022112073001576)]
4. T. Tsukahara, Y. Seki, H. Kawamura and D. Tochio, "DNS of turbulent channel flow at very low Reynolds numbers," *Proceedings of 4th International Symposium on Turbulence and Shear Flow Phenomena* (2005), 935–940. [[Web Page](https://doi.org/10.1615/TSFP4.1550)]
5. A. Prigent, G. Grégoire, H. Chaté, O. Dauchot and W. van Saarloos, "Large-scale finite-wavelength modulation within turbulent shear flows," [*Physical Review Letters*](https://journals.aps.org/prl/), **89** (2002), 014501. [[Web Page](https://doi.org/10.1103/PhysRevLett.89.014501)]

## 📄 文書テンプレート

レポートや学位論文の作成に使用する文書テンプレートです．
いずれも使用方法のマニュアル付きで，学外の方も自由にお使いいただけます．

### Typst

- [`report_template_Typst`](https://github.com/matsukawa-group/report_template_Typst)
  - レポート・研究資料用
  - [Typst の使用方法マニュアル](https://github.com/matsukawa-group/report_template_Typst/blob/main/template-manual/template-manual.pdf) 付き
- [`Meiji-mech_thesis_template_Typst`](https://github.com/matsukawa-group/Meiji-mech_thesis_template_Typst)
  - 明治大学理工学部機械工学科の卒業論文用
  - [Typst の使用方法マニュアル](https://github.com/matsukawa-group/Meiji-mech_thesis_template_Typst/blob/main/template-manual/template-manual.pdf) 付き

### LaTeX

- [`report_template_LaTeX`](https://github.com/matsukawa-group/report_template_LaTeX)
  - レポート・研究資料用
  - [LaTeX の使用方法マニュアル](https://github.com/matsukawa-group/report_template_LaTeX/blob/main/template-manual/template-manual.pdf) 付き

## 🔰 研究の始め方

研究室に配属された学生向けの資料です．

- [`lab-startup`](https://github.com/matsukawa-group/lab-startup)
  - 【未完成】研究室に配属された学生が最初に読む項目．研究ツールや環境構築について記載．
- [`GitHub_tutorial`](https://github.com/matsukawa-group/GitHub_tutorial)
  - 【未完成】研究室に新しく配属された学生向けの Git/GitHub チュートリアル．

---

**Matsukawa Group** <br>
Fluid Mechanics Laboratory, <br>
Department of Mechanical Engineering, <br>
School of Science and Technology, <br>
Meiji University
