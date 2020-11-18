<?php
                $array=["a","b","c","d","e","f","g"];
                echo var_dump($array);
                // echo "<br>";
                // $array[]='d';
                // echo var_dump($array);
                // echo "<br>";
                // //array_pushは追加したい要素を入れる配列を入れると
                // array_push($array,"e","f","g");
                // //これが
                // //array(4) { [0]=> string(1) "a" [1]=> string(1) "b" [2]=> string(1) "c" [3]=> string(1) "d" }
                // //こうなる
                // // array(7) { [0]=> string(1) "a" [1]=> string(1) "b" [2]=> string(1) "c" [3]=> string(1) "d" [4]=> string(1) "e" [5]=> string(1) "f" [6]=> string(1) "g" }
                // $add_array=["h","i","j"];
                //配列を指定すると
                // array_push($array,$add_array);
                // echo var_dump($array);
                // echo "<br>";
                //こうなる
                // array(8) { [0]=> string(1) "a" [1]=> string(1) "b" [2]=> string(1) "c" [3]=> string(1) "d" [4]=> string(1) "e" [5]=> string(1) "f" [6]=> string(1) "g" [7]=> array(3) { [0]=> string(1) "h" [1]=> string(1) "i" [2]=> string(1) "j" } }
                // echo var_dump($array);
                // echo "<br>";
                // echo var_dump($array[7]);
                // echo "<br>";
                // echo var_dump($array[7][0]);
                // echo "<br>";
                //こうなる
                //array(3) { [0]=> string(1) "h" [1]=> string(1) "i" [2]=> string(1) "j" }
                //string(1) "h"
                $array_slice=array_slice($array,3,2);
                echo var_dump($array_slice);
                echo "<br>";
                echo "<pre>";
                echo var_dump($array_slice);
                echo "</pre>";
                echo "<br>";

                echo "<br>";
                $array=[
                    "a"=>"asd",
                    "b"=>"bnm",
                    "c"=>"cvb"
                ];
                echo "<br>";
                echo "<pre>";
                echo var_dump($array);
                echo "</pre>";
                echo "<br>";
                $array=[
                    1=>"asd",
                    2=>"bnm",
                    3=>"cvb"
                ];
                echo "<br>";
                echo "<pre>";
                echo var_dump($array);
                echo "</pre>";
                $array=["asd","bnm","cvb"];
                echo "<br>";
                echo "<pre>";
                echo var_dump($array);
                echo "</pre>";
        ?>
