# Visualizing Newick Formats 
This is a small web service to quickly visualise newick formats

![alt tag](https://raw.github.com/daviddao/visualise-newick/master/pic.png)


## Tree display

You can easily change the way how your tree is displayed by editing the opts in index.html

````
var opts = {
        el : document.getElementById("yourDiv"),
        tree : {
            data : "(homo_sapiens:12,(mus_musculus:12,(danio_rerio:13,(pan_troglodytes:9,(taeniopygia_guttata:10,callithrix_jacchus:11):12):12):10);",  
            width : 500,
            height : 30,
            scale : false,
            layoutInput : "vertical",
        },
        label : {
            fontsize : 18,
            usePics : true, 
            pics : {
                pictureWidth : 20,
                pictureHeight : 20,
            },
        },
        nodes : {
            toggle : true, 
            select: false, 
            size : 5,
            fill : "grey",
            stroke : "black",
            selectedFill : "steelblue",
            selectedSize : 4,
        },
};
````
