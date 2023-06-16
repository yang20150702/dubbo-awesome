# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.033 ops/ms
# Warmup Iteration   2: 2.358 ops/ms
# Warmup Iteration   3: 5.011 ops/ms
Iteration   1: 5.683 ops/ms
Iteration   2: 5.814 ops/ms
Iteration   3: 5.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.800 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (5.683, 5.800, 5.904), stdev = 0.111
  CI (99.9%): [3.773, 7.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.524 ops/ms
# Warmup Iteration   2: 4.830 ops/ms
# Warmup Iteration   3: 5.851 ops/ms
Iteration   1: 6.395 ops/ms
Iteration   2: 6.225 ops/ms
Iteration   3: 6.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.316 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (6.225, 6.316, 6.395), stdev = 0.086
  CI (99.9%): [4.753, 7.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.720 ops/ms
# Warmup Iteration   2: 4.902 ops/ms
# Warmup Iteration   3: 5.784 ops/ms
Iteration   1: 5.665 ops/ms
Iteration   2: 5.409 ops/ms
Iteration   3: 5.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.673 ±(99.9%) 4.886 ops/ms [Average]
  (min, avg, max) = (5.409, 5.673, 5.944), stdev = 0.268
  CI (99.9%): [0.787, 10.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.387 ops/ms
# Warmup Iteration   2: 3.964 ops/ms
# Warmup Iteration   3: 4.902 ops/ms
Iteration   1: 4.893 ops/ms
Iteration   2: 5.436 ops/ms
Iteration   3: 5.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.154 ±(99.9%) 4.964 ops/ms [Average]
  (min, avg, max) = (4.893, 5.154, 5.436), stdev = 0.272
  CI (99.9%): [0.190, 10.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.948 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.679 ±(99.9%) 0.018 ms/op
Iteration   1: 5.556 ±(99.9%) 0.010 ms/op
Iteration   2: 5.240 ±(99.9%) 0.017 ms/op
Iteration   3: 5.394 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.397 ±(99.9%) 2.884 ms/op [Average]
  (min, avg, max) = (5.240, 5.397, 5.556), stdev = 0.158
  CI (99.9%): [2.512, 8.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.599 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.012 ms/op
Iteration   1: 5.145 ±(99.9%) 0.013 ms/op
Iteration   2: 5.109 ±(99.9%) 0.012 ms/op
Iteration   3: 5.342 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.199 ±(99.9%) 2.288 ms/op [Average]
  (min, avg, max) = (5.109, 5.199, 5.342), stdev = 0.125
  CI (99.9%): [2.911, 7.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.228 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.851 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.425 ±(99.9%) 0.011 ms/op
Iteration   1: 5.593 ±(99.9%) 0.016 ms/op
Iteration   2: 5.770 ±(99.9%) 0.015 ms/op
Iteration   3: 5.451 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.605 ±(99.9%) 2.909 ms/op [Average]
  (min, avg, max) = (5.451, 5.605, 5.770), stdev = 0.159
  CI (99.9%): [2.696, 8.514] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.571 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.627 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.875 ±(99.9%) 0.013 ms/op
Iteration   1: 6.663 ±(99.9%) 0.020 ms/op
Iteration   2: 6.627 ±(99.9%) 0.010 ms/op
Iteration   3: 6.357 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.549 ±(99.9%) 3.047 ms/op [Average]
  (min, avg, max) = (6.357, 6.549, 6.663), stdev = 0.167
  CI (99.9%): [3.502, 9.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.193 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 7.119 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.963 ±(99.9%) 0.030 ms/op
Iteration   1: 5.556 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  25.777 ms/op
                 createUser·p0.9999: 33.176 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   2: 5.605 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.421 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 34.688 ms/op
                 createUser·p1.00:   35.455 ms/op

Iteration   3: 5.260 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.799 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  27.930 ms/op
                 createUser·p0.9999: 30.895 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175589
  mean =      5.470 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 64547 
    [ 5.000,  7.500) = 102292 
    [ 7.500, 10.000) = 7049 
    [10.000, 12.500) = 1146 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     33.110 ms/op
     p(99.9990) =     35.108 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.683 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.809 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.152 ±(99.9%) 0.016 ms/op
Iteration   1: 5.308 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   8.348 ms/op
                 existUser·p0.99:   11.332 ms/op
                 existUser·p0.999:  22.995 ms/op
                 existUser·p0.9999: 26.574 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 5.236 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.455 ms/op
                 existUser·p0.95:   7.102 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  16.234 ms/op
                 existUser·p0.9999: 29.586 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 5.117 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.585 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  26.859 ms/op
                 existUser·p0.9999: 30.310 ms/op
                 existUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183829
  mean =      5.219 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 105232 
    [ 5.000,  7.500) = 70052 
    [ 7.500, 10.000) = 6133 
    [10.000, 12.500) = 1557 
    [12.500, 15.000) = 455 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     30.594 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.395 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.612 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.584 ±(99.9%) 0.021 ms/op
Iteration   1: 5.308 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  26.038 ms/op
                 getUser·p0.9999: 34.136 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   2: 5.536 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  23.921 ms/op
                 getUser·p0.9999: 28.399 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   3: 5.077 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  26.181 ms/op
                 getUser·p0.9999: 30.553 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181159
  mean =      5.300 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 85656 
    [ 5.000,  7.500) = 87720 
    [ 7.500, 10.000) = 5645 
    [10.000, 12.500) = 1465 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     31.581 ms/op
     p(99.9990) =     37.237 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.262 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.542 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.600 ±(99.9%) 0.023 ms/op
Iteration   1: 6.286 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  27.165 ms/op
                 listUser·p0.9999: 37.880 ms/op
                 listUser·p1.00:   40.042 ms/op

Iteration   2: 6.519 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.924 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  30.114 ms/op
                 listUser·p0.9999: 33.873 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   3: 6.733 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  23.856 ms/op
                 listUser·p0.9999: 36.372 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147455
  mean =      6.507 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3653 
    [ 5.000, 10.000) = 139867 
    [10.000, 15.000) = 3485 
    [15.000, 20.000) = 153 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 79 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.650 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      7.733 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.017 ms/op
     p(99.9000) =     28.970 ms/op
     p(99.9900) =     36.635 ms/op
     p(99.9990) =     39.669 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.800 ± 2.027  ops/ms
ClientPb.existUser                       thrpt       3   6.316 ± 1.563  ops/ms
ClientPb.getUser                         thrpt       3   5.673 ± 4.886  ops/ms
ClientPb.listUser                        thrpt       3   5.154 ± 4.964  ops/ms
ClientPb.createUser                       avgt       3   5.397 ± 2.884   ms/op
ClientPb.existUser                        avgt       3   5.199 ± 2.288   ms/op
ClientPb.getUser                          avgt       3   5.605 ± 2.909   ms/op
ClientPb.listUser                         avgt       3   6.549 ± 3.047   ms/op
ClientPb.createUser                     sample  175589   5.470 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.821           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  183829   5.219 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.340           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.088           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.048           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.704           ms/op
ClientPb.getUser                        sample  181159   5.300 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.539           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.152           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.437           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.581           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  147455   6.507 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.650           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.733           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.017           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.635           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.042           ms/op
