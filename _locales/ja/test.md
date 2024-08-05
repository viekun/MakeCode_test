### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa

## Step 1
モナリザは有名な微笑みを失った。Agentが持っている`白色の彩釉テラコッタブロック`を、縦6ブロック、横6ブロックの正方形の輪郭になるように配置してください。

#### ~ tutorialhint 
Use the ``||agent.agent move||`` to move your Agent and then ``||agent.agent place||`` to PLACE the `White Glazed Terracotta` we've given the Agent. Repeat ``||agent.agent move||`` and ``||agent.agent place||`` until the right number of blocks are placed.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```