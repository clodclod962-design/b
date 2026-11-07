# MyMod (Fabric 1.20.1, client-side)

Right Shift - меню. ЛКМ - вкл/выкл модуль, ПКМ - настройки, СКМ - назначить клавишу (ESC - снять), колесо - прокрутка.
Настройки и бинды: .minecraft/config/mymod.json

Модули:
- Combat: AutoTotem(Z), AutoPearl(X), KillAura(R, +TargetStrafe, Criticals), Velocity(V)
- Movement: Sprint, Flight(G), Speed, NoFall, Spider
- Player: FastPlace, AutoRespawn, NoHunger, AutoEat
- Render: Fullbright(B), ESP(N), StorageESP(J), Tracers, Xray(H), BlockOutline
- Effects: ChinaHat(K, неоновая шляпа), Particles, HitEffects, Ambience (небо/время/погода)
- Misc: HUD

Сборка: GitHub Actions (.github/workflows/build.yml) -> Artifacts -> mymod-jar. Нужен Fabric API 0.92.2+1.20.1.
Xray не работает вместе с Sodium/Embeddium/Iris.
