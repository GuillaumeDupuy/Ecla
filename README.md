# Ecla

## Requirements

Install Go 1.19 or later.

### For Windows:

1. Download the Go installer for Windows from the official Go website: https://go.dev/dl/

2. Open the installation file and follow the instructions to install Go.

3. After the installation, open the Windows command prompt (cmd) and type "go version". This should display the version of Go you just installed.

### For Linux:

1. Use the following command to install Go:

```bash
wget https://dl.google.com/go/go1.19.linux-amd64.tar.gz
sudo tar -xvf go1.19.linux-amd64.tar.gz
sudo mv go /usr/local
```

2. Add the following line to your ~/.bashrc file for adding Go to the PATH environment variable:

```bash
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```

3. Save and close the file. Then, reload your terminal and type "go version". This should display the version of Go you just installed.

## Execute Ecla

1. Clone the repository:

```bash
git clone https://github.com/Eclalang/Ecla.git
cd Ecla
```

2. Execute the following command to create the executable file:

```bash
go build -o .
```

> For Windows, the executable file is named "Ecla.exe". For Linux, the executable file is named "Ecla".

3. Execute the following command to run the program:

For Linux:

```bash
./Ecla <file>
```

For Windows:

```bash
Ecla.exe <file>
```

> Replace ```<file>``` with the path to the file you want to execute.

## Example

#### hello-world file

For Linux:

![image](https://github.com/GuillaumeDupuy/Ecla/assets/56391911/cda6ce8a-35c9-4bd7-8cbc-f749876878b6)

For Windows:
  
![image](https://github.com/GuillaumeDupuy/Ecla/assets/56391911/cc12aaeb-493a-420c-88e0-8a325cb38175)
