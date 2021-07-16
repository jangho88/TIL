\# 1. 기본 스타일 설정
\#plt.style.use('default')
plt.rcParams['figure.figsize'] = (7, 4)
plt.rcParams['font.size'] = 8# 3. 그래프 그리기
fig, ax1 = plt.subplots()ax1.plot(df_m_join_1["자치구"], df_m_join_1["1인당 총 도시림 면적"], '-s', color='green', linewidth=2, alpha=0.5, label='Price')
ax1.set_xlabel('자치구')
ax1.set_ylabel('공원 도림 면적')
ax1.tick_params(axis='both', direction='in')ax2 = ax1.twinx()
ax2.bar(df_m_join_1["자치구"], df_m_join_1["우울감 경험률"], color='deeppink', label='Demand', alpha=0.7, width=0.7)
\#ax2.set_ylim(0, 18)
\#ax2.set_ylabel(r'Demand ($\times10^6$)')
ax2.tick_params(axis='y', direction='in')plt.show()

