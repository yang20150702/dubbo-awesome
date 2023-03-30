# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.951 ops/ms
# Warmup Iteration   2: 2.224 ops/ms
# Warmup Iteration   3: 4.003 ops/ms
Iteration   1: 4.779 ops/ms
Iteration   2: 5.062 ops/ms
Iteration   3: 5.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.103 ±(99.9%) 6.317 ops/ms [Average]
  (min, avg, max) = (4.779, 5.103, 5.468), stdev = 0.346
  CI (99.9%): [≈ 0, 11.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.388 ops/ms
# Warmup Iteration   2: 4.104 ops/ms
# Warmup Iteration   3: 5.264 ops/ms
Iteration   1: 5.799 ops/ms
Iteration   2: 5.888 ops/ms
Iteration   3: 6.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.021 ±(99.9%) 5.658 ops/ms [Average]
  (min, avg, max) = (5.799, 6.021, 6.375), stdev = 0.310
  CI (99.9%): [0.363, 11.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.849 ops/ms
# Warmup Iteration   2: 4.399 ops/ms
# Warmup Iteration   3: 5.465 ops/ms
Iteration   1: 5.463 ops/ms
Iteration   2: 5.452 ops/ms
Iteration   3: 5.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.535 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (5.452, 5.535, 5.689), stdev = 0.134
  CI (99.9%): [3.098, 7.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 3.813 ops/ms
# Warmup Iteration   3: 4.644 ops/ms
Iteration   1: 4.949 ops/ms
Iteration   2: 4.988 ops/ms
Iteration   3: 4.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.875 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (4.687, 4.875, 4.988), stdev = 0.164
  CI (99.9%): [1.888, 7.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 24.449 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 8.261 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 7.131 ±(99.9%) 0.019 ms/op
Iteration   1: 7.916 ±(99.9%) 0.019 ms/op
Iteration   2: 7.314 ±(99.9%) 0.020 ms/op
Iteration   3: 7.245 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.492 ±(99.9%) 6.739 ms/op [Average]
  (min, avg, max) = (7.245, 7.492, 7.916), stdev = 0.369
  CI (99.9%): [0.753, 14.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.826 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.408 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.617 ±(99.9%) 0.015 ms/op
Iteration   1: 5.638 ±(99.9%) 0.008 ms/op
Iteration   2: 5.571 ±(99.9%) 0.014 ms/op
Iteration   3: 5.361 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.523 ±(99.9%) 2.633 ms/op [Average]
  (min, avg, max) = (5.361, 5.523, 5.638), stdev = 0.144
  CI (99.9%): [2.890, 8.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.427 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.819 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.007 ms/op
Iteration   1: 5.927 ±(99.9%) 0.010 ms/op
Iteration   2: 6.043 ±(99.9%) 0.013 ms/op
Iteration   3: 5.933 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.968 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (5.927, 5.968, 6.043), stdev = 0.066
  CI (99.9%): [4.770, 7.166] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.371 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.311 ±(99.9%) 0.016 ms/op
Iteration   1: 6.531 ±(99.9%) 0.014 ms/op
Iteration   2: 6.978 ±(99.9%) 0.016 ms/op
Iteration   3: 6.593 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.701 ±(99.9%) 4.415 ms/op [Average]
  (min, avg, max) = (6.531, 6.701, 6.978), stdev = 0.242
  CI (99.9%): [2.286, 11.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.417 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 7.352 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.097 ±(99.9%) 0.025 ms/op
Iteration   1: 5.958 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.652 ms/op
                 createUser·p0.90:   7.668 ms/op
                 createUser·p0.95:   8.315 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  24.357 ms/op
                 createUser·p0.9999: 27.519 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 5.606 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  14.677 ms/op
                 createUser·p0.9999: 29.773 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   3: 5.529 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.087 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  28.053 ms/op
                 createUser·p0.9999: 33.833 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168624
  mean =      5.692 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 59196 
    [ 5.000,  7.500) = 95527 
    [ 7.500, 10.000) = 11436 
    [10.000, 12.500) = 1637 
    [12.500, 15.000) = 415 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     32.917 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.549 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 6.678 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.207 ±(99.9%) 0.017 ms/op
Iteration   1: 5.238 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  20.928 ms/op
                 existUser·p0.9999: 24.824 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 5.638 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   10.242 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 34.297 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   3: 6.097 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.816 ms/op
                 existUser·p0.90:   8.159 ms/op
                 existUser·p0.95:   9.208 ms/op
                 existUser·p0.99:   12.100 ms/op
                 existUser·p0.999:  25.857 ms/op
                 existUser·p0.9999: 34.653 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170216
  mean =      5.636 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 69321 
    [ 5.000,  7.500) = 87201 
    [ 7.500, 10.000) = 10764 
    [10.000, 12.500) = 2141 
    [12.500, 15.000) = 494 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     20.177 ms/op
     p(99.9900) =     34.207 ms/op
     p(99.9990) =     35.184 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.990 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 8.036 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.030 ms/op
Iteration   1: 5.745 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.487 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 27.539 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 6.121 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.900 ms/op
                 getUser·p0.50:   6.078 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   8.684 ms/op
                 getUser·p0.99:   11.380 ms/op
                 getUser·p0.999:  27.116 ms/op
                 getUser·p0.9999: 29.793 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 5.856 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.520 ms/op
                 getUser·p0.95:   8.331 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  29.495 ms/op
                 getUser·p0.9999: 35.167 ms/op
                 getUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162544
  mean =      5.903 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 48898 
    [ 5.000,  7.500) = 94762 
    [ 7.500, 10.000) = 16779 
    [10.000, 12.500) = 1452 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     32.825 ms/op
     p(99.9990) =     36.396 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.267 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 8.694 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 6.648 ±(99.9%) 0.027 ms/op
Iteration   1: 6.344 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.435 ms/op
                 listUser·p0.999:  26.413 ms/op
                 listUser·p0.9999: 30.733 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 6.642 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  31.190 ms/op
                 listUser·p0.9999: 34.550 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.602 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.646 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  25.262 ms/op
                 listUser·p0.9999: 32.002 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147077
  mean =      6.526 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 4906 
    [ 5.000,  7.500) = 118558 
    [ 7.500, 10.000) = 19641 
    [10.000, 12.500) = 2848 
    [12.500, 15.000) = 716 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      6.128 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     27.916 ms/op
     p(99.9900) =     33.335 ms/op
     p(99.9990) =     36.064 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.103 ± 6.317  ops/ms
ClientPb.existUser                       thrpt       3   6.021 ± 5.658  ops/ms
ClientPb.getUser                         thrpt       3   5.535 ± 2.436  ops/ms
ClientPb.listUser                        thrpt       3   4.875 ± 2.986  ops/ms
ClientPb.createUser                       avgt       3   7.492 ± 6.739   ms/op
ClientPb.existUser                        avgt       3   5.523 ± 2.633   ms/op
ClientPb.getUser                          avgt       3   5.968 ± 1.198   ms/op
ClientPb.listUser                         avgt       3   6.701 ± 4.415   ms/op
ClientPb.createUser                     sample  168624   5.692 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.846           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.341           ms/op
ClientPb.existUser                      sample  170216   5.636 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.241           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.928           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.177           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.207           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  162544   5.903 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.469           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.690           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.825           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.749           ms/op
ClientPb.listUser                       sample  147077   6.526 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.646           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.846           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.916           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
