#!/bin/bash

read -p "User? " username

sudo adduser $username

read -p "Nome da primeira pasta: " pasta

mkdir $pasta

cd $pasta/

read -p "Nome da segunda pasta: " pasta2

mkdir $pasta2

read -p "Nome da terceira pasta: " pasta3

mkdir $pasta3

read -p "Caro $username , pressione na tecla ENTER para ter privilegios de sudo"

sudo usermod -aG sudo $username
