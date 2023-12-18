<h1 align="center">
  <a href="https://discord.gg/QXFKXaTRHB">
    <picture>
      <img alt="MINEREKT" src="https://github.com/Vedming/MINEREKT/blob/main/icon.png?raw=true" width="300">
    </picture>
  </a>
</h1>

# [DISCORD](https://discord.gg/QXFKXaTRHB)

# CONFIGURAÇÃO E DOWNLOAD DO SKLAUNCHER:

Download do sklauncher: https://skmedix.pl/downloads 

Baixe e instale o Java JDK 17 na opção de x64bits .msi https://adoptium.net/temurin/releases/?version=17

Crie uma conta pelo site e de upload em sua skin, coloque seu nick no launcher no modo offline e logue

Ao entrar no launcher vá em Launcher Settings e ative a opção "Allow Xmx Arguments"

Volte ao menu e clique no + ao lado de Installations Manager

Marque as seguintes opções: Versão 1.19.2 e Forge 43.3.5

Abra a categoria More Options e coloque em Java Executable o diretorio aonde você instalou o seu Java, geralmente ficará assim: C:\Program Files\Java\jdk-17\bin\javaw.exe

Logo depois arraste para baixo e vá nas opções de JVM Arguments e cole os seguintes argumentos:

```
-Xmx8G -Xms8G -XX:+UnlockExperimentalVMOptions -XX:+UnlockDiagnosticVMOptions -XX:+AlwaysPreTouch -XX:+DisableExplicitGC -XX:+UseNUMA -XX:NmethodSweepActivity=1 -XX:ReservedCodeCacheSize=400M -XX:NonNMethodCodeHeapSize=12M -XX:ProfiledCodeHeapSize=194M -XX:NonProfiledCodeHeapSize=194M -XX:-DontCompileHugeMethods -XX:MaxNodeLimit=240000 -XX:NodeLimitFudgeFactor=8000 -XX:+UseVectorCmov -XX:+PerfDisableSharedMem -XX:+UseFastUnorderedTimeStamps -XX:+UseCriticalJavaThreadPriority -XX:ThreadPriorityPolicy=1 -XX:AllocatePrefetchStyle=3  -XX:+UseG1GC -XX:MaxGCPauseMillis=37 -XX:+PerfDisableSharedMem -XX:G1HeapRegionSize=16M -XX:G1NewSizePercent=23 -XX:G1ReservePercent=20 -XX:SurvivorRatio=32 -XX:G1MixedGCCountTarget=3 -XX:G1HeapWastePercent=20 -XX:InitiatingHeapOccupancyPercent=10 -XX:G1RSetUpdatingPauseTimePercent=0 -XX:MaxTenuringThreshold=1 -XX:G1SATBBufferEnqueueingThresholdPercent=30 -XX:G1ConcMarkStepDurationMillis=5.0 -XX:G1ConcRSHotCardLimit=16 -XX:G1ConcRefinementServiceIntervalMillis=150 -XX:GCTimeRatio=99 -XX:+UseLargePages -XX:LargePageSizeInBytes=2m
```

(-XmxXG e -XmsXG irão definir sua RAM alocada, o recomendado é de 6 - 12 e o mínimo 4, edite para o valor desejado)

# INSTALAÇÃO DO MODPACK

Apague toda sua .minecraft caso você já tenha o mine instalado

Arraste todo o conteúdo da .zip baixado para a .minecraft e substitua os arquivos.
