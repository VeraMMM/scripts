#!/bin/bash

echo "Пошла жара"

check_success() {
    if [ $? -eq 0 ]; then
        echo "Успешно"
    else
        echo "Ошибка при выполнении: $1"
        exit 1
    fi
}
sudo apt update
sudo apt upgrade -y
sudo apt dist-upgrade -y
sudo apt autoremove -y
sudo apt autoclean

echo "Всё супер"
