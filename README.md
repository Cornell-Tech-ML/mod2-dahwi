[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)

# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

- Docs: https://minitorch.github.io/

- Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

### The number of points for each dataset: 50

### Simple:

#### Hyperparameters:

- Learning rate: 0.5
- Number of epochs: 500
- Size of hidden layer: 2

#### Time per epoch: 0.141s

#### Logs:

```
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 34.08047989283159, correct: 29
Epoch: 20/500, loss: 33.97983855363779, correct: 29
Epoch: 30/500, loss: 33.964277343235956, correct: 29
Epoch: 40/500, loss: 33.95511958516878, correct: 29
Epoch: 50/500, loss: 33.94260200369112, correct: 29
Epoch: 60/500, loss: 33.30567444140289, correct: 29
Epoch: 70/500, loss: 29.574015517323982, correct: 29
Epoch: 80/500, loss: 21.93662835389461, correct: 40
Epoch: 90/500, loss: 14.03204872904695, correct: 47
Epoch: 100/500, loss: 9.97104536427194, correct: 49
Epoch: 110/500, loss: 7.652929947294046, correct: 50
Epoch: 120/500, loss: 6.069313684369979, correct: 50
Epoch: 130/500, loss: 5.0613905823814385, correct: 50
Epoch: 140/500, loss: 4.330344976121727, correct: 50
Epoch: 150/500, loss: 3.7740722074468493, correct: 50
Epoch: 160/500, loss: 3.333679946261419, correct: 50
Epoch: 170/500, loss: 2.9753235422624402, correct: 50
Epoch: 180/500, loss: 2.677803666140006, correct: 50
Epoch: 190/500, loss: 2.4267717134153446, correct: 50
Epoch: 200/500, loss: 2.2127204414873303, correct: 50
Epoch: 210/500, loss: 2.028207979192048, correct: 50
Epoch: 220/500, loss: 1.8679984196272679, correct: 50
Epoch: 230/500, loss: 1.7277985658052437, correct: 50
Epoch: 240/500, loss: 1.6044222482952848, correct: 50
Epoch: 250/500, loss: 1.495228824507075, correct: 50
Epoch: 260/500, loss: 1.3981296433923354, correct: 50
Epoch: 270/500, loss: 1.3113178853159075, correct: 50
Epoch: 280/500, loss: 1.23654160468516, correct: 50
Epoch: 290/500, loss: 1.1679002267479033, correct: 50
Epoch: 300/500, loss: 1.1049081131276957, correct: 50
Epoch: 310/500, loss: 1.0494943781888686, correct: 50
Epoch: 320/500, loss: 0.9987321037590857, correct: 50
Epoch: 330/500, loss: 0.9520838718503914, correct: 50
Epoch: 340/500, loss: 0.9091010745882862, correct: 50
Epoch: 350/500, loss: 0.8694020256962041, correct: 50
Epoch: 360/500, loss: 0.8326327491400879, correct: 50
Epoch: 370/500, loss: 0.7985094153596356, correct: 50
Epoch: 380/500, loss: 0.766784670095494, correct: 50
Epoch: 390/500, loss: 0.7372232619302964, correct: 50
Epoch: 400/500, loss: 0.7096257812443727, correct: 50
Epoch: 410/500, loss: 0.6838235010623949, correct: 50
Epoch: 420/500, loss: 0.6596254049155421, correct: 50
Epoch: 430/500, loss: 0.6369296577919257, correct: 50
Epoch: 440/500, loss: 0.615595434555017, correct: 50
Epoch: 450/500, loss: 0.5955168957775472, correct: 50
Epoch: 460/500, loss: 0.5765711098111501, correct: 50
Epoch: 470/500, loss: 0.558694016334377, correct: 50
Epoch: 480/500, loss: 0.5417927750679408, correct: 50
Epoch: 490/500, loss: 0.525791192811307, correct: 50
Epoch: 500/500, loss: 0.5106279154029487, correct: 50
```

#### Plots:

![Plot](simple_sc.png)
![Plot](simple_loss.png)

### Diag:

#### Hyperparameters:

- Learning rate: 0.5
- Number of epochs: 500
- Size of hidden layer: 2

#### Time per epoch: 0.096s

#### Logs:

```
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 7.402856046438806, correct: 48
Epoch: 20/500, loss: 6.986897777785992, correct: 48
Epoch: 30/500, loss: 6.673004152991697, correct: 48
Epoch: 40/500, loss: 6.349873193410151, correct: 48
Epoch: 50/500, loss: 6.002795263444534, correct: 48
Epoch: 60/500, loss: 5.6258133064875215, correct: 48
Epoch: 70/500, loss: 5.219175607564605, correct: 48
Epoch: 80/500, loss: 4.7912482871534765, correct: 48
Epoch: 90/500, loss: 4.359143201608827, correct: 48
Epoch: 100/500, loss: 3.945932461163321, correct: 48
Epoch: 110/500, loss: 3.5722458158518675, correct: 48
Epoch: 120/500, loss: 3.2605047564336056, correct: 49
Epoch: 130/500, loss: 3.020460715815685, correct: 49
Epoch: 140/500, loss: 2.819011137817124, correct: 49
Epoch: 150/500, loss: 2.648474612407751, correct: 49
Epoch: 160/500, loss: 2.5027052882125806, correct: 49
Epoch: 170/500, loss: 2.3780881871814983, correct: 49
Epoch: 180/500, loss: 2.2751490127162843, correct: 49
Epoch: 190/500, loss: 2.181022240718921, correct: 49
Epoch: 200/500, loss: 2.097835474697921, correct: 49
Epoch: 210/500, loss: 2.0235501329675625, correct: 49
Epoch: 220/500, loss: 1.9566713823109705, correct: 49
Epoch: 230/500, loss: 1.8959867335672775, correct: 49
Epoch: 240/500, loss: 1.8405098730230574, correct: 49
Epoch: 250/500, loss: 1.7894634323233727, correct: 49
Epoch: 260/500, loss: 1.743390188129278, correct: 49
Epoch: 270/500, loss: 1.6993529849552056, correct: 49
Epoch: 280/500, loss: 1.6591091419004171, correct: 49
Epoch: 290/500, loss: 1.621324359951787, correct: 49
Epoch: 300/500, loss: 1.584486456260091, correct: 49
Epoch: 310/500, loss: 1.550200818317739, correct: 49
Epoch: 320/500, loss: 1.5186500409189838, correct: 49
Epoch: 330/500, loss: 1.489355754685275, correct: 49
Epoch: 340/500, loss: 1.4608703504253902, correct: 49
Epoch: 350/500, loss: 1.433142751714886, correct: 49
Epoch: 360/500, loss: 1.4060505973544821, correct: 49
Epoch: 370/500, loss: 1.3795230899182975, correct: 49
Epoch: 380/500, loss: 1.353505727469912, correct: 49
Epoch: 390/500, loss: 1.32795219362722, correct: 49
Epoch: 400/500, loss: 1.3028233334655954, correct: 49
Epoch: 410/500, loss: 1.2780862665564299, correct: 49
Epoch: 420/500, loss: 1.2537136153716397, correct: 49
Epoch: 430/500, loss: 1.2296907522239928, correct: 50
Epoch: 440/500, loss: 1.2060005874429724, correct: 50
Epoch: 450/500, loss: 1.182615405087986, correct: 50
Epoch: 460/500, loss: 1.159524000142696, correct: 50
Epoch: 470/500, loss: 1.1367264624673223, correct: 50
Epoch: 480/500, loss: 1.1142107974621451, correct: 50
Epoch: 490/500, loss: 1.091972889815313, correct: 50
Epoch: 500/500, loss: 1.0700074888661857, correct: 50
```

#### Plots:

![Plot](diag.png)

### Split:

#### Hyperparameters:

- Learning rate: 0.1
- Number of epochs: 700
- Size of hidden layer: 8

#### Time per epoch: 0.473s

#### Logs:

```
Epoch: 0/700, loss: 0, correct: 0
Epoch: 10/700, loss: 33.1847751250165, correct: 30
Epoch: 20/700, loss: 32.372204538614845, correct: 30
Epoch: 30/700, loss: 32.03007433266892, correct: 30
Epoch: 40/700, loss: 31.716549694480996, correct: 32
Epoch: 50/700, loss: 31.401615818771223, correct: 34
Epoch: 60/700, loss: 31.035623434545855, correct: 35
Epoch: 70/700, loss: 30.652287257067137, correct: 35
Epoch: 80/700, loss: 30.24024432526012, correct: 37
Epoch: 90/700, loss: 29.688429727153657, correct: 38
Epoch: 100/700, loss: 29.20039965611754, correct: 40
Epoch: 110/700, loss: 28.706755955144807, correct: 39
Epoch: 120/700, loss: 28.198072328105095, correct: 39
Epoch: 130/700, loss: 27.67650977391902, correct: 41
Epoch: 140/700, loss: 27.128524178019553, correct: 41
Epoch: 150/700, loss: 26.551398545668025, correct: 40
Epoch: 160/700, loss: 25.94427672951328, correct: 40
Epoch: 170/700, loss: 25.30584827951948, correct: 40
Epoch: 180/700, loss: 24.628503383468253, correct: 42
Epoch: 190/700, loss: 23.946754491094065, correct: 42
Epoch: 200/700, loss: 23.25090818583115, correct: 43
Epoch: 210/700, loss: 22.530863896995804, correct: 43
Epoch: 220/700, loss: 21.79031491778041, correct: 44
Epoch: 230/700, loss: 21.04409462448524, correct: 44
Epoch: 240/700, loss: 20.290337572343073, correct: 44
Epoch: 250/700, loss: 19.530747152953396, correct: 44
Epoch: 260/700, loss: 18.779283136213383, correct: 45
Epoch: 270/700, loss: 18.030564316228322, correct: 45
Epoch: 280/700, loss: 17.25613375176074, correct: 46
Epoch: 290/700, loss: 16.47962056490278, correct: 47
Epoch: 300/700, loss: 15.676439273532347, correct: 47
Epoch: 310/700, loss: 14.812764473288839, correct: 47
Epoch: 320/700, loss: 13.96536252686061, correct: 48
Epoch: 330/700, loss: 13.194614368231338, correct: 49
Epoch: 340/700, loss: 12.48187808475003, correct: 49
Epoch: 350/700, loss: 11.820037979500821, correct: 49
Epoch: 360/700, loss: 11.219312646482313, correct: 49
Epoch: 370/700, loss: 10.663784666641195, correct: 49
Epoch: 380/700, loss: 10.150181525187836, correct: 50
Epoch: 390/700, loss: 9.667491145246297, correct: 50
Epoch: 400/700, loss: 9.213467467742095, correct: 50
Epoch: 410/700, loss: 8.786809385154006, correct: 50
Epoch: 420/700, loss: 8.386156194972203, correct: 50
Epoch: 430/700, loss: 8.01031672489208, correct: 50
Epoch: 440/700, loss: 7.659415206439698, correct: 50
Epoch: 450/700, loss: 7.331651920164846, correct: 50
Epoch: 460/700, loss: 7.024234653461791, correct: 50
Epoch: 470/700, loss: 6.735818736420791, correct: 50
Epoch: 480/700, loss: 6.465145520409976, correct: 50
Epoch: 490/700, loss: 6.210982850479037, correct: 50
Epoch: 500/700, loss: 5.972185046488548, correct: 50
Epoch: 510/700, loss: 5.747652071012133, correct: 50
Epoch: 520/700, loss: 5.5363885734515685, correct: 50
Epoch: 530/700, loss: 5.337437136669997, correct: 50
Epoch: 540/700, loss: 5.149907557669271, correct: 50
Epoch: 550/700, loss: 4.972993208156654, correct: 50
Epoch: 560/700, loss: 4.805976458681445, correct: 50
Epoch: 570/700, loss: 4.6481268465864956, correct: 50
Epoch: 580/700, loss: 4.498780943900995, correct: 50
Epoch: 590/700, loss: 4.357362259314701, correct: 50
Epoch: 600/700, loss: 4.2233185302506815, correct: 50
Epoch: 610/700, loss: 4.094599891338748, correct: 50
Epoch: 620/700, loss: 3.966795684064509, correct: 50
Epoch: 630/700, loss: 3.8453249004609904, correct: 50
Epoch: 640/700, loss: 3.73163492269828, correct: 50
Epoch: 650/700, loss: 3.6274171844820318, correct: 50
Epoch: 660/700, loss: 3.528489249404322, correct: 50
Epoch: 670/700, loss: 3.4341827419239075, correct: 50
Epoch: 680/700, loss: 3.344185582858863, correct: 50
Epoch: 690/700, loss: 3.258223504472864, correct: 50
Epoch: 700/700, loss: 3.176118841948056, correct: 50
```

#### Plots:

![Plot](split.png)

### XOR:

#### Hyperparameters:

- Learning rate: 0.5
- Number of epochs: 450
- Size of hidden layer: 16

#### Time per epoch: 1.477s

#### Logs:

```
Epoch: 0/450, loss: 0, correct: 0
Epoch: 10/450, loss: 27.487113392116797, correct: 38
Epoch: 20/450, loss: 23.61863602168389, correct: 41
Epoch: 30/450, loss: 20.008054824381716, correct: 43
Epoch: 40/450, loss: 18.373005195366936, correct: 44
Epoch: 50/450, loss: 17.130007744276572, correct: 44
Epoch: 60/450, loss: 16.181082759538114, correct: 44
Epoch: 70/450, loss: 14.82121587170639, correct: 45
Epoch: 80/450, loss: 13.465060004913852, correct: 45
Epoch: 90/450, loss: 13.70916145723347, correct: 45
Epoch: 100/450, loss: 11.86703693628776, correct: 45
Epoch: 110/450, loss: 11.317333214100852, correct: 46
Epoch: 120/450, loss: 11.008131540796612, correct: 44
Epoch: 130/450, loss: 9.98417762724209, correct: 45
Epoch: 140/450, loss: 8.752946378517768, correct: 46
Epoch: 150/450, loss: 8.324504872507923, correct: 46
Epoch: 160/450, loss: 9.416683377298067, correct: 45
Epoch: 170/450, loss: 7.478931879575026, correct: 47
Epoch: 180/450, loss: 5.744875854750247, correct: 48
Epoch: 190/450, loss: 8.967522822798603, correct: 45
Epoch: 200/450, loss: 4.228614653111024, correct: 49
Epoch: 210/450, loss: 2.8371526264689226, correct: 50
Epoch: 220/450, loss: 2.6174211622063988, correct: 50
Epoch: 230/450, loss: 2.3884730740523037, correct: 50
Epoch: 240/450, loss: 2.1938901844104572, correct: 50
Epoch: 250/450, loss: 2.0808530556995897, correct: 50
Epoch: 260/450, loss: 2.1195275038084644, correct: 49
Epoch: 270/450, loss: 2.1799837939435682, correct: 49
Epoch: 280/450, loss: 2.6813347649019175, correct: 49
Epoch: 290/450, loss: 2.850638287878092, correct: 49
Epoch: 300/450, loss: 2.4288379441743704, correct: 49
Epoch: 310/450, loss: 2.038844073551116, correct: 49
Epoch: 320/450, loss: 1.858842382974927, correct: 49
Epoch: 330/450, loss: 1.7469729154948415, correct: 49
Epoch: 340/450, loss: 1.674176045920391, correct: 49
Epoch: 350/450, loss: 1.627751378530954, correct: 49
Epoch: 360/450, loss: 1.6148794426815027, correct: 49
Epoch: 370/450, loss: 1.6765145923864178, correct: 49
Epoch: 380/450, loss: 2.0596084112923108, correct: 49
Epoch: 390/450, loss: 2.388450704571683, correct: 49
Epoch: 400/450, loss: 2.228298294432427, correct: 49
Epoch: 410/450, loss: 1.9487236763298015, correct: 49
Epoch: 420/450, loss: 1.469717235741998, correct: 49
Epoch: 430/450, loss: 0.9020347984772178, correct: 50
Epoch: 440/450, loss: 0.8496534393416978, correct: 50
Epoch: 450/450, loss: 0.8179839264258219, correct: 50
```

#### Plots:

![Plot](xor.png)
