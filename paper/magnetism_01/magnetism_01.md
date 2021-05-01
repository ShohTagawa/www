---
layout: single
classes: wide
title: Massalski & Laughlin
---
## The surprising role of magnetism on the phase stability of Fe (Ferro)
*Calphad* Volume 33, Issue 1, March 2009, Pages 3-7

### Abstract
We discuss the phase stability of the important element Fe in terms of the contributions to stability from the various forms of magnetism that exist in Fe. We point out that the ferromagnetic Fe is not cubic and that it is reasonable to return the beta phase of Fe to the phase diagrams based on Fe to designate paramagnetic BCC form of iron. We give a working definition of a phase, which includes the term “order parameter” following the insights of Landau.


### まとめ
Feの相安定性について、磁性の観点から検討した論文

#### はじめに
多くの元素の位相安定性は，次のようなパターンを示す。
1. 低温での構造選択には主にエンタルピーの高低が関与している。
2. 高温では、より高いエントロピーを持つ構造（相）が安定する。

そのため、温度上昇に伴ってよく起こる相転移は、稠密構造から、もっと疎な結晶構造への変化である。(例；Ti hcp → bcc)

Feはこのパターンに当てはまらない。この論文は、Feの安定性を磁性から議論する。

#### Fe の安定性に関する事実
1. Fe の低温相は、BCC相(α-Fe)である。
2. この BCC Fe 相は、加熱すると約 910 ∘C で FCC 相(γ-Fe)に相転移する。
3. FCC相は、加熱により約1400℃でBCC相(δ-Fe)に変化する。

過去には、β相と呼ばれる相も考えられていた。本論文では、これらのFe相の安定性の温度範囲について、Feの熱力学に及ぼす磁気転移の影響を考慮して議論する。

#### Feの安定性に関する事実の考察
Fe の相転移は、1成分系(unary system)において磁気効果が構造安定性に重要な寄与をする興味深い例である。Feの温度/圧力相図は、上に挙げた「事実」を示している。常圧で加熱したときの全体的な変化の順序は次のようにまとめられる。
$$ α → γ → δ → liquid $$
圧力を加えると、これらの遷移の温度が変化する（クラペイロン式を用いて計算できる）。また、約125 kbar以上の圧力をかけると、Feはhcp相を取るようになる。

各構造の原子あたりの体積（Ω）と接近する原子間距離（d）の常圧における温度変化の傾向を図1に示す。BCCの値は、FCCの値よりも大きい。したがって、BCC構造はより"open"な構造とみなすことができ、より多くの振動選択(vibrational choices)を可能にし、FCCよりも振動エントロピーを大きくしている。この特徴により、BCC相のギブスエネルギーの負のTS項は、FCC相よりも温度とともに急速に増加する。FCC構造の12個の原子は、BCCの最も近い8個の原子よりもわずかに離れている（$$ d_bcc $$）が、BCC構造の次の6個の原子の距離は、最も近い接近距離を超えている（$$ d_bcc < d_fcc $$）。このような総合的な理由から、BCC構造はFCC構造に比べて最密充填ではないとみなされている。両構造の原子あたりの体積差が非常に小さいことは、両構造の全エネルギーが同程度であることを示しており、2つの異なる結晶構造のFeの原子間の結合が本質的に金属的であることを裏付けている。

<figure>
  <img src="/paper/magnetism_01/fig1.jpg" alt="Temperature dependence of lattice parameters and the volume per atom in α and γ Fe.">
</figure>

ここで、上に挙げた相についての事実に目を向けると、当然の疑問が浮かぶ。

1. なぜBCC型のFeは低温で安定なのか？通常、FCCやHCPのような密着型同素体は低温で安定である。これは、密着型同素体では一般にエンタルピーが低下し、エントロピーはあまり重要ではないからである。

2. 加熱するとBCC相がFCC相に変化するのはなぜか？一般的に、加熱すると、よりopenな構造、つまり、より高い振動エントロピーを持つ構造が、より安定な相になるはずなので、これもまた逆のように思える。一般的に、ほとんどの元素では、高温になるほどよりオープンな構造が観察される。

3. なぜFCCはさらに高温でBCCに戻るのか？BCCの大きな振動エントロピーだけが、この変換に関与しているのか？

最後に、なぜ現在の文献では、変化の順序にβ相が含まれていないのか、という疑問がある。
相の安定性に関する疑問に答えるためには、問題となっている相の比熱に注目しなければならない（図2)。
<figure>
  <img src="/paper/magnetism_01/fig2.jpg" alt="Schematic specific heat (CV) versus temperature curves for the α and γ phases of Fe.">
</figure>

1184 K (910 ∘C)での加熱によるα→γ変換は、変換温度で両方の相が存在し、比熱の明確な不連続性があり、変換の潜熱を生じさせるという点で、一次相変換の明確な例である。同じことが、1665 K（1392 ∘C）でのγからδへの変換にも当てはまる。しかし、比熱曲線には2つの興味深い部分があります。すなわち、γ相で約50Kに現れるピークと、α相で1042Kに現れる別のピークである。これらのピークは、材料を加熱し続けるためには、材料に供給するエネルギーを増やす必要があることによる。この比熱の増加は、低温側の相をそれぞれの常磁性状態に変化させるために、反強磁性体であるFCC Feの秩序スピンと強磁性体であるBCC Feの秩序スピンをランダム化する必要があることと関係している。

反強磁性のfcc Feから常磁性のfcc Feへの転移温度は、ネール温度(Néel temperature)と呼ばれる。反強磁性(AF)の磁気的な秩序をもつ物質では、磁気スピンが隣接するスピンに対して逆方向に並んでいるため、秩序があるとみなすことができる。これは、銅に埋め込まれたミクロンサイズの準安定なγ-Fe粒子で起こることが実験的に実証されており、そのFeは冷却してもFCCのままである。反強磁性的な配列では、反対側の磁気モーメントが互いに打ち消し合うため、全体の磁化はゼロになる。しかし、この反強磁性配列は構造エネルギーに寄与しており、磁気モーメントをランダム化するためには熱が必要となる。この遷移は、図2のfcc相のCp曲線の小さなピークで示されている。図2は、FCCおよびBCC Fe相の両方の傾向を示しており、準安定領域への外挿（破線で示す）もあるが、これは非常に合理的であると思われる。どちらの磁気状態も、低温ではそれぞれの結晶構造を安定させる。

質問1は、次のように答えることができる。0Kでは、BCC相の強磁性秩序により、その内部エネルギー（およびエンタルピー）は、反強磁性（および常磁性）FCC相の内部エネルギー（およびエンタルピー）よりも小さくなる、すなわち、$$ H_α(FM) < Hγ $$. これは、強磁性体BCC Feの整列した磁気モーメントの大きな交換エネルギーが、その内部エネルギーを大きく低下させるためである。このように、強磁性BCC Feは、FCCよりも密度が低くても、低温では平衡相となる。

質問2と3への答えはより複雑で、内部エネルギーだけでなく、エントロピーの影響も関わってくる。これらの質問に答えるためには、それぞれの相の比熱の温度に対する挙動をより詳細に検討する必要がある（図2参照）。どちらの曲線にも、磁気転移に対応するピークが見られる。ここでは、αとγ相のエントロピーの2つの側面、すなわち、振動エントロピーと磁気スピンエントロピーについて考える。先に述べたように、振動エントロピーは通常、FCC構造よりもBCC構造の方が大きい。これが、高温ではBCC構造の方がFCC構造よりも安定している理由である。しかし、Feの場合には、スピンの乱れによるエントロピーも考慮しなければならない。

低温では、γ Feの反強磁性から常磁性への転移により、構成上のスピン・エントロピーが増大し、密に充填されたγ相の全体的なエントロピーが、より緩く充填された強磁性のα相のエントロピーよりも大きくなる。この過剰なエントロピー（ニール温度での磁気スピンの乱れによる）が、相のギブスエネルギーの式からわかるように、より高い温度でのγ相の出現の原因となる。
γ相のギブズエネルギーの式からもわかるように、温度が高くなるとギブズエネルギーが減少し続けるため、最終的には負のTS項が原因となってγ相のギブズエネルギーが低くなる。したがって、FCC相がBCC相に置き換わるのは約910℃のときであり、このときに構造変化が起こる。この加熱によるBCCからFCCへの変化は、通常のFCCからBCCへの変化とは逆である。なぜなら、Feの場合、平衡相を決定するのは格子振動エントロピー項ではなく、スピンの乱れによるエントロピーだからである。

これらの変換を図4に示す。910 ∘Cで曲線が交差し、BCCからFCCへの相変化が生じている。しかし、さらに加熱すると、キュリー温度範囲内のα相の過剰な比熱によって、負のTS項が重要になり、その結果、曲線は約1400 ∘Cで再び交差する。このように、α相中の磁気スピンのランダム化による大きなエントロピーと、その大きな振動エントロピーとがδ相として表示されることで、BCC相が再び現れたのである。


Feにおける磁気効果の重要性は、以下のようにまとめられる。
1.もしγ Feが極低温で反強磁性体でなかった場合、強磁性体であるBCC相はエンタルピーが低く、常磁性体であるBCC相はエントロピーが高いため、γ Feがより高温の相として形成されるほど安定になることはない。極低温での反強磁性状態は、加熱時のニール温度の範囲で磁気ランダム化時の比熱ピークに寄与し、この状況は、その後、FCC相の自由エネルギーを910 ∘℃のBCC相の自由エネルギーよりも下げるのに十分である。

2.もし、FeのNeel転移温度が図3に示した温度よりも少し高ければ、FCC（γ）Feは、この相と競合するほど安定にはならない可能性が高い。これは、γ相の自由エネルギーが、その比熱曲線を温度で積分した結果、十分に大きな負のTSエントロピー項を持たず、上記の910 ∘Cに対して安定になるように自由エネルギーを十分に下げることができないからである。図2を見ると、γ Feのギブズ自由エネルギー曲線は、α/δ Feのギブズ自由エネルギー曲線よりも上に位置し続けることになります。

1. 同様に、相の強磁性から常磁性へのキュリー転移温度がもう少し低い温度であれば、大きな負のTS項（これも比熱曲線を温度で積分した結果）により、BCC自由エネルギー曲線は、温度の上昇に伴ってすぐに下向きにねじれ、すべての温度で相を相対的に安定させる傾向がある。したがって、やはり高温ではFCC（γ）Feは形成されないかもしれない。


明らかに、磁気効果（その特定の臨界それぞれの大きさと、対応する臨界乱れ温度を含む）がなければ、純粋なFeにFCC相は存在しないだろう。

よく知られているように、鉄の合金ではあらゆる種類の相変態が起こる。合金の添加によって、図3のような図におけるニール温度とキュリー温度のそれぞれの位置だけでなく、比熱のピークの大きさも変化する。また、2つの相のギブズ自由エネルギー曲線のそれぞれの位置と形の両方が、結果として得られる相図の答えとなる。冶金学的に言えば、それぞれの合金の相図において「ループ」は広がる傾向にあるか、または縮んで閉じる傾向にある。その結果、鉄の合金は、多様な相変態と熱処理の機会を持つ魅力的な分野を構成している。これには明らかに磁気的な相互作用が重要な役割を果たしている。反強磁性転移や強磁性から常磁性への転移に伴うニール温度やキュリー温度の位置、比熱の大きさをモデル化することは、結果として得られる熱力学的パラメータの一部を定量化する興味深い機会となるだろう。

#### β Feの相はどうなるのか？
最後の疑問は、なぜFeの相図にはβ相がないのか、ということです。

実は、19世紀から20世紀にかけて、鉄の相図にはβ相が示されていましたが、その後の出版物では削除されている。その理由の一つは、長年、冶金業界では、強磁性体から常磁性体への変化は相変化ではないと考えられていたためだ。このような冶金学者の混乱は、磁性相の構造の対称性に対する理解が不完全であったことと、相の定義が狭かったことに起因する。

このように、磁気転移の領域では、電気抵抗や比熱などの特性変化がさまざまな温度範囲で生じている証拠があるにもかかわらず、構造の変化が検出されないため、その転移は相変化ではないと考えられていたのである。強磁性相と常磁性相の両方が同じ構造を持っていれば、それらは同じ相であると考えられた。それゆえ、β（常磁性体BCC Feの記号であった）の呼称は削除された。現在では、BCC Feの常磁性と強磁性の両方が同じギリシャ文字「α」で表される。

しかし、BCC Feの常磁性体と強磁性体は同じ相なのだろうか？一般的な教科書に載っている相の定義の代表的なものは

1. "相とは、その性質と組成が均一で、物理的に他の部分とは異なるシステムの部分と定義することができる..." 。
2. 「...平衡状態には，比容積，組成，構造などの同じ特性を示す領域が含まれる。これらの領域が相を構成する」。
3. "相とは、同じ集中的な特性を持つ、構造的に均質な物質の部分と定義される。したがって、相は均一な組成であり、その集中的な特性は一定である」。
4. 「特定の外部制約の下で平衡状態に達した原子または分子の集合体は、1つまたは複数の均質で物理的に異なる領域からなる。各タイプの領域は、密度、組成などの固有の特性を定義する共通のパラメータセットによって区別されることがあり、それらはアセンブリの相を構成する。2つの相は，異なる凝集状態，固体内の異なる構造配置，または異なる組成を示す場合には区別できる．
{: .notice--info}

これらの定義を受け入れるならば、常磁性相は強磁性相とは異なる磁気的性質を持つため、これらの定義だけで、常磁性から強磁性への「変化」は確かに相変化であることを意味する。しかし、相には明確な「構造」があるとされていたため、問題が生じた。X線回折で調べた限りでは、強磁性Feの構造は常磁性Feの構造と同じであった。そのため、Feがキュリー温度領域で磁性を失っても、相の変化は起こらないと考えられていた。

しかし、転移においては、磁気的な変化に伴って、対称性の変化、つまり構造の変化が起こるはずである。強磁性ドメイン内では磁気スピンがFeの[001]方向に沿って並んでいるため、強磁性Feの対称性は実際には空間群I4/mの正方晶である。このことは、[100]方向と[010]方向が、磁化のある[001]方向と一致しないことからもわかる。加熱によって起こる強磁性から常磁性への変化は、高次の転移と呼ばれるものである。磁気的な乱れに対応するα Feの比熱曲線に大きなピークがあることからもわかるように、比熱などの特性の変化はさまざまな温度で起こる。このような相変化に伴う温度をキュリー温度という。純粋なFeの場合、その値は約1042K(769 ∘C)である。このように、磁気状態の変化は、対称性の変化、つまり構造の変化とともに起こる。これは、上記の相変化の定義のすべてにおいてそうである。

Christianの定義では "common set of parameters"という表現が使われているが、オーダーパラメーターについての明確な言及がないという点で、上記の定義は完全ではない。オーダーパラメータは，1930年代にLandauによって開発された概念である．これを含めて，我々は以下のように「相」の定義を提案する．

*相*とは，熱力学的平衡に達した系の物理的に異なる領域であり，その物理的特性を規定する特定の秩序パラメータ（$$ η_1, η_2, ... $$）のセットを持つものである．
したがって、*相の変化*は、その秩序パラメータの1つ以上が、ある値から別の値へ、またはゼロから非ゼロの値へ（またはその逆へ）不連続に変化するときに起こるものである。
{: .notice--info}

このように、強磁性相が常磁性相に変化した場合、その物質の磁化である磁気秩序変数は、加熱によるキュリー温度を通過する際にゼロではない値からゼロに変化するため、相変化が起こったことになる。つまり、本当はβ Fe相が存在していて、それが常磁性体のBCCといえる。

#### まとめ
重要な元素であるFeの相安定性について考察した。Feの安定性を完全に解明するためには、Feに存在する様々な形態の磁性を含める必要があることを示しました。その過程で、強磁性Feは立方体ではないことを指摘し、Feの相をFeの相図に戻して常磁性BCC Feとすることが妥当であることを示しました。また、相の定義として、ランダウの洞察に倣って「オーダーパラメーター」という言葉を使っています。

校正時の注意事項
本論文の最終版を提出した後、Journal of Phase Equilibria Vol.22 No.6 pp.631-644 (2001)に掲載されたQing Chen and Bo Sundmanによる論文「Modeling of Thermodynamic Properties for Bcc, Fcc, Liquid, and Amorphous Iron」を発見しました。631-644 (2001)という論文を発見しました。この論文では、私たちの論文で定性的に扱っている側面のいくつかを定量的に扱っています。

### Remote theme method

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install as a remote theme:

1. Create/replace the contents of your `Gemfile` with the following:


### Remote theme method

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install as a remote theme:

1. Create/replace the contents of your `Gemfile` with the following:

   ```ruby
   source "https://rubygems.org"

   gem "github-pages", group: :jekyll_plugins
   gem "jekyll-include-cache", group: :jekyll_plugins
   ```

2. Add `jekyll-include-cache` to the `plugins` array of your `_config.yml`.

3. Fetch and update bundled gems by running the following [Bundler](https://bundler.io/) command:

   ```bash
   bundle
   ```

4. Add `remote_theme: "mmistakes/minimal-mistakes@4.22.0"` to your `_config.yml` file. Remove any other `theme:` or `remote_theme:` entry.

You may also optionally specify a branch, [tag](https://github.com/mmistakes/minimal-mistakes/tags), or commit to use by appending an @ and the Git ref (e.g., `mmistakes/minimal-mistakes@4.9.0` or `mmistakes/minimal-mistakes@bbf3cbc5fd64a3e1885f3f99eb90ba92af84063d`). This is useful when rolling back to older versions of the theme. If you don't specify a Git ref, the latest on `master` will be used.

**Looking for an example?** Use the [Minimal Mistakes remote theme starter](https://github.com/mmistakes/mm-github-pages-starter/generate) for the quickest method of getting a GitHub Pages hosted site up and running. Generate a new repository from the starter, replace sample content with your own, and configure as needed.
{: .notice--info}

---

**Note:** Your Jekyll site should be viewable immediately at <http://USERNAME.github.io>. If it's not, you can force a rebuild by **Customizing Your Site** (see below for more details).
{: .notice--warning}

If you're hosting several Jekyll based sites under the same GitHub username you will have to use Project Pages instead of User Pages. Essentially you rename the repo to something other than **USERNAME.github.io** and create a `gh-pages` branch off of `master`. For more details on how to set things up check [GitHub's documentation](https://help.github.com/articles/user-organization-and-project-pages/).

<figure>
  <img src="{{ '/assets/images/mm-gh-pages.gif' | relative_url }}" alt="creating a new branch on GitHub">
</figure>

You can also install the theme by copying all of the theme files[^structure] into your project.

To do so fork the [Minimal Mistakes theme](https://github.com/mmistakes/minimal-mistakes/fork), then rename the repo to **USERNAME.github.io** --- replacing **USERNAME** with your GitHub username.

<figure>
  <img src="{{ '/assets/images/mm-theme-fork-repo.png' | relative_url }}" alt="fork Minimal Mistakes">
</figure>

**GitHub Pages Alternatives:** Looking to host your site for free and install/update the theme painlessly? [Netlify][netlify-jekyll], [GitLab Pages][gitlab-jekyll], and [Continuous Integration (CI) services][ci-jekyll] have you covered. In most cases all you need to do is connect your repository to them, create a simple configuration file, and install the theme following the [Ruby Gem Method](#ruby-gem-method) above.
{: .notice--info}

[netlify-jekyll]: https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/
[gitlab-jekyll]: https://about.gitlab.com/2016/04/07/gitlab-pages-setup/
[ci-jekyll]: https://jekyllrb.com/docs/deployment/automated/#continuous-integration-service

### Remove the Unnecessary

If you forked or downloaded the `minimal-mistakes-jekyll` repo you can safely remove the following folders and files:

- `.editorconfig`
- `.gitattributes`
- `.github`
- `/docs`
- `/test`
- `CHANGELOG.md`
- `minimal-mistakes-jekyll.gemspec`
- `README.md`
- `screenshot-layouts.png`
- `screenshot.png`

**Note:** If forking the theme be sure to update `Gemfile` as well. The one found at the root of the project is for building the theme's Ruby gem and is missing dependencies. To properly setup a [`Gemfile`](https://github.com/mmistakes/minimal-mistakes/blob/master/docs/Gemfile) with the theme, consult the "[Install Dependencies](https://mmistakes.github.io/minimal-mistakes/docs/installation/#install-dependencies)" section.
{: .notice--warning}

## Setup Your Site

Depending on the path you took installing Minimal Mistakes you'll setup things a little differently.

**ProTip:** The source code and content files for this site can be found in the [`/docs` folder](https://github.com/mmistakes/minimal-mistakes/tree/master/docs) if you want to copy or learn from them.
{: .notice--info}

### Starting Fresh

Starting with an empty folder and `Gemfile` you'll need to copy or re-create this [default `_config.yml`](https://github.com/mmistakes/minimal-mistakes/blob/master/_config.yml) file. For a full explanation of every setting be sure to read the [**Configuration**]({{ "/docs/configuration/" | relative_url }}) section.

From `v4.5.0` onwards, Minimal Mistakes theme-gem comes bundled with the necessary data files for localization.
They will be picked up automatically if you have the [`jekyll-data`](https://github.com/ashmaroli/jekyll-data) plugin installed.
If you're hosting on GitHub Pages, you can copy the [`_data/ui-text.yml`][ui-text.yml] file into your repository for the localization feature to work.

You'll need to create and edit these data files to customize them:

- [`_data/ui-text.yml`][ui-text.yml] - UI text [documentation]({{ "/docs/ui-text/" | relative_url }})
- [`_data/navigation.yml`][navigation.yml] - navigation [documentation]({{ "/docs/navigation/" | relative_url }})

  [ui-text.yml]: https://github.com/mmistakes/minimal-mistakes/blob/master/_data/ui-text.yml
  [navigation.yml]: https://github.com/mmistakes/minimal-mistakes/blob/master/_data/navigation.yml

### Starting from `jekyll new`

Scaffolding out a site with the `jekyll new` command requires you to modify a few files that it creates.

Edit `_config.yml`. Then:

- Replace `<site root>/index.md` with a modified [Minimal Mistakes `index.html`](https://github.com/mmistakes/minimal-mistakes/blob/master/index.html). Be sure to enable pagination if using the [`home` layout]({{ "/docs/layouts/#home-page" | relative_url }}) by adding the necessary lines to **_config.yml**.
- Change `layout: post` in `_posts/0000-00-00-welcome-to-jekyll.markdown` to `layout: single`.
- Remove `about.md`, or at the very least change `layout: page` to `layout: single` and remove references to `icon-github.html` (or [copy to your `_includes`](https://github.com/jekyll/minima/tree/master/_includes) if using it).

### Migrating to Gem Version

If you're migrating a site already using Minimal Mistakes and haven't customized any of the theme files things upgrading will be easier for you.

Start by removing the following folders and any files within them: 

```terminal
├── _includes
├── _layouts
├── _sass
├── assets
|  ├── css
|  ├── fonts
|  └── js
```

You won't need these anymore as they're bundled with the theme gem --- unless you intend to [override them](https://jekyllrb.com/docs/themes/#overriding-theme-defaults).

**Note:** When clearing out the `assets` folder be sure to leave any files you've added and need. This includes images, CSS, or JavaScript that aren't already [bundled in the theme](https://github.com/mmistakes/minimal-mistakes/tree/master/assets). 
{: .notice--warning}

From `v4.5.0` onwards, the default language files are read-in automatically via the [`jekyll-data`](https://github.com/ashmaroli/jekyll-data) plugin if it's installed. For sites hosted with GitHub Pages, you still need to copy the [`_data/ui-text.yml`][ui-text.yml] file because the `jekyll-data` plugin [is unsupported on GitHub Pages](https://docs.github.com/en/github/working-with-github-pages/about-github-pages-and-jekyll#plugins).

If you customized any of these files leave them alone, and only remove the untouched ones. If done correctly your modified versions should [override](https://jekyllrb.com/docs/themes/#overriding-theme-defaults) the versions bundled with the theme and be used by Jekyll instead.

#### Update Gemfile

Replace `gem "github-pages` or `gem "jekyll"` with `gem "jekyll", "~> 3.5"`. You'll need the latest version of Jekyll[^update-jekyll] for Minimal Mistakes to work and load all of the theme's assets properly, this line forces Bundler to do that.

[^update-jekyll]: You could also run `bundle update jekyll` to update Jekyll.

Add the Minimal Mistakes theme gem: 

```ruby
gem "minimal-mistakes-jekyll"
```

When finished your `Gemfile` should look something like this:

```ruby
source "https://rubygems.org"

gem "jekyll", "~> 3.7"
gem "minimal-mistakes-jekyll"
```

Then run `bundle update` and add `theme: minimal-mistakes-jekyll` to your `_config.yml`.

**v4 Breaking Change:** Paths for image headers, overlays, teasers, [galleries]({{ "/docs/helpers/#gallery" | relative_url }}), and [feature rows]({{ "/docs/helpers/#feature-row" | relative_url }}) have changed and now require a full path. Instead of just `image: filename.jpg` you'll need to use the full path eg: `image: /assets/images/filename.jpg`. The preferred location is now `/assets/images/` but can be placed elsewhere or externally hosted. This applies to image references in `_config.yml` and `author.yml` as well.
{: .notice--danger}

---

That's it! If all goes well running `bundle exec jekyll serve` should spin-up your site.
