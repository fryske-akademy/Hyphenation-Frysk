# Hyphenation-Frysk
Software for adding hyphenation marks to multi-syllable words in Frisian text.

Follow the instructions below to build the Docker image and launch the container.

### 1. Clone the Repo

```
git clone https://github.com/fryske-akademy/Hyphenation-Frysk.git
cd Hyphenation-Frysk
```

### 2. Build the Docker Image

```
docker build -t hyphenation-frysk .
```

### 3. Run the Container

```
docker run -p 3838:3838 hyphenation
```

### 4. View in Browser

Open:
http://localhost:3838
