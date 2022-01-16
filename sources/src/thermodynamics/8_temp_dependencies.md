### Температурные зависимости

> Теплоёмкость — приращение температуры при соответствующем приращении теплоты.

\\[ C_l = \frac{\delta Q}{dT} \\]

Нас будут интересовать два случая расчёта теплоёмкости:

1. \\( V = \text{const} \\), то \\[ C_V = \left. \frac{\partial U}{\partial T} \right\rvert_V \\]
2. \\( P = \text{const} \\), то \\[ C_P = \left. \frac{\partial H}{\partial T} \right\rvert_P \\]

Можно проинтегрировать по температуре:

\\[ U = U_0 + \int\limits_{T_0}^{T} C_V(t) dt \\]
\\[ H = H_0 + \int\limits_{T_0}^{T} C_P(t) dt \\]

Это позволяет получать тепловой эффект. Следующие два соотношения называются `законами Кирхгофа`:

\\[ \Delta_r U = \Delta_r U_0 + \int\limits_{T_0}^{T} \Delta_r C_V(t) dt = -Q_V(T)\\]
\\[ \Delta_r H = \Delta_r H_0 + \int\limits_{T_0}^{T} \Delta_r C_P(t) dt -Q_P(T)\\]