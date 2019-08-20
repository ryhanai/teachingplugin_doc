# プロジェクトファイルについて

ロボットはタスクではなくChoreonoidのプロジェクトファイルで指定されています。デフォルトのプロジェクトファイル（teaching_plugin.cnoid）ではNextageOPENになっています。他に、双腕配置のUR3のもの（teaching_plugin_UR3dual.cnoid）があります。

teachingPluginで利用可能なロボットのモデルはURDF形式、あるいは[OpenHRP形式](http://choreonoid.org/ja/manuals/1.6/handling-models/modelfile/modelfile-openhrp.html)です（最新のChoreonoidの標準形式はBody形式という別の形式に変更されています）。
<!-- URDF形式からOpenHRP形式のロボットモデルファイルを作る場合、[simtrans](http://fkanehiro.github.io/simtrans/html-ja/usage.html)等のツールを上手く使える場合があります。 -->
