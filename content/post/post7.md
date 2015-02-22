+++
date = "2015-02-21T23:32:01+01:00"
draft = true
title = "Player class on java"
tags = ["news","a"]
categories = ["test"]
image = "/images/featured/1.jpg"
featured = ["Featured"]
+++

<pre class="line-numbers"><code class="language-java">
public class Player {

    private Texture playerTexture;
    private float x;
    private float y;


    public Player()
    {
        playerTexture = new Texture("player.png");
    }

    public void render(SpriteBatch batch){
        batch.draw(playerTexture,x,y);
    }
}

</code></pre>

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipisicing elit omnis. Obcaecati, 
 omnis modi facilis. Quod fugiat deserunt animi cum maiores omnis, explicabo aliquam, ullam voluptatum veniam quo amet distinctio natus architecto quae! cum maiores omnis, explicabo aliquam consectetur adipisicing elit

Lorem ipsum dolor sit amet, consectetur adipisicing elit omnis. Obcaecati, omnis modi facilis. Quod fugiat deserunt animi cum maiores omnis, explicabo aliquam, ullam voluptatum veniam quo amet distinctio natus architecto quae! cum maiores omnis, explicabo aliquam consectetur adipisicing elit

Lorem ipsum dolor sit amet, consectetur adipisicing elit omnis. Obcaecati, omnis modi facilis. Quod fugiat deserunt animi cum maiores omnis, explicabo aliquam, ullam voluptatum veniam quo amet distinctio natus architecto quae! cum maiores omnis, explicabo aliquam consectetur adipisicing elit

Lorem ipsum dolor sit amet, consectetur adipisicing elit omnis. Obcaecati, omnis modi facilis. Quod fugiat deserunt animi cum maiores omnis, explicabo aliquam, ullam voluptatum veniam quo amet distinctio natus architecto quae! cum maiores omnis, explicabo aliquam consectetur adipisicing elit

