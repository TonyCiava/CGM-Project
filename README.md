# CGM-Project
2D Rogue-like game

## Import Assets

## Create Scene

## Create a Player Prefab



#### 1. Create empty game object

#### 2. Selects and add Animation to empty object and save inside ./assets/animations/animations
 Create Idle , Attack , Chop

#### 3. Copy Controller in  ./assets/animations/animatorController

#### 4. Set object Tags And Layer (Blockinglayer) 

#### 5. Set sprite renderer SortingLayer (units) 

#### 6. Add RigidBody2D component to Object - Manage Movement
 set bodytype kinematic

#### 7. Add BoxCollider2D component to Object
 set box collider size 

#### 8. Create Prefab

## Create a Enemy Prefab

#### 1. Same

## Create a Enemy 2 Prefab

#### 1. Copy Enemy 1 Object

#### 2. Go to Animator State Diagram

#### 3. Create Animator Override Controller (right click on ./Assets/Animations/AnimatorController and create Override Controller)

#### 4. Overide with enemy 1 Controller

#### 5. In enemy 2 Inspector change Animator Controller to Enemy2


## Save as Main in ./Assets/Scene
