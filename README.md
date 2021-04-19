# maze_dqn
迷路課題を深層強化学習(DQN)を用いて解く

s, s_nextは, '', '#', 'S', 'G' の値
s_num, s_num_nextは, マスの２次元配列　例　[1,1]
state, state_nextは, s_num, s_num_nextをテンソルに変換したもの　例 tensor[1,1]
