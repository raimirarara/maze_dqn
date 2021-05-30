# maze_dqn
迷路課題を深層強化学習(DQN)を用いて解きました。
Colaboratoryを用いて実行してください。
maze.txtというファイルをColabにアップロードしてから実行してください。

s, s_nextは, ' ', '#', 'S', 'G' の値

s_num, s_num_nextは, マスの２次元配列　例 [1,1]

state, state_nextは, s_num, s_num_nextをテンソルに変換したもの　例 tensor[1,1]
