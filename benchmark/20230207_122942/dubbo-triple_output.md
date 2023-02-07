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
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 6.563 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.640 ops/ms
Iteration   2: 9.769 ops/ms
Iteration   3: 9.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.731 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (9.640, 9.731, 9.783), stdev = 0.079
  CI (99.9%): [8.293, 11.169] (assumes normal distribution)


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
# Warmup Iteration   1: 3.607 ops/ms
# Warmup Iteration   2: 9.594 ops/ms
# Warmup Iteration   3: 10.296 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.882 ops/ms
Iteration   3: 10.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.493 ±(99.9%) 6.703 ops/ms [Average]
  (min, avg, max) = (10.151, 10.493, 10.882), stdev = 0.367
  CI (99.9%): [3.790, 17.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ops/ms
# Warmup Iteration   2: 9.503 ops/ms
# Warmup Iteration   3: 10.053 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 9.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.061 ±(99.9%) 4.463 ops/ms [Average]
  (min, avg, max) = (9.784, 10.061, 10.248), stdev = 0.245
  CI (99.9%): [5.598, 14.523] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.316 ops/ms
Iteration   1: 8.543 ops/ms
Iteration   2: 8.523 ops/ms
Iteration   3: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (8.523, 8.550, 8.584), stdev = 0.031
  CI (99.9%): [7.988, 9.112] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.093 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.004 ms/op
Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.087 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.063, 3.087, 3.109), stdev = 0.023
  CI (99.9%): [2.668, 3.506] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.355 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
Iteration   2: 3.105 ±(99.9%) 0.005 ms/op
Iteration   3: 3.036 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.025, 3.055, 3.105), stdev = 0.044
  CI (99.9%): [2.258, 3.853] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.612 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
Iteration   2: 3.301 ±(99.9%) 0.006 ms/op
Iteration   3: 3.238 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.228 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.145, 3.228, 3.301), stdev = 0.078
  CI (99.9%): [1.798, 4.659] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.381 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.006 ms/op
Iteration   1: 3.757 ±(99.9%) 0.004 ms/op
Iteration   2: 3.822 ±(99.9%) 0.004 ms/op
Iteration   3: 3.743 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.774 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.743, 3.774, 3.822), stdev = 0.042
  CI (99.9%): [3.004, 4.544] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.754 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  12.863 ms/op
                 createUser·p0.9999: 19.294 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 21.816 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 27.172 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304635
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26923 
    [ 2.500,  5.000) = 272404 
    [ 5.000,  7.500) = 4542 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     25.085 ms/op
     p(99.9990) =     27.883 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  15.614 ms/op
                 existUser·p0.9999: 25.945 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  9.400 ms/op
                 existUser·p0.9999: 24.043 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307322
  mean =      3.123 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20464 
    [ 2.500,  5.000) = 282202 
    [ 5.000,  7.500) = 3800 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     14.576 ms/op
     p(99.9900) =     24.725 ms/op
     p(99.9990) =     26.636 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.770 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.221 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  16.017 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 19.434 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  14.685 ms/op
                 getUser·p0.9999: 23.853 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296149
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23027 
    [ 2.500,  5.000) = 262741 
    [ 5.000,  7.500) = 9510 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.841 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.120 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.011 ms/op
Iteration   1: 3.644 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.226 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 19.864 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.655 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  12.916 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 20.007 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260034
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 252832 
    [ 5.000,  7.500) = 5545 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     20.454 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.731 ± 1.438  ops/ms
ClientPb.existUser                       thrpt       3  10.493 ± 6.703  ops/ms
ClientPb.getUser                         thrpt       3  10.061 ± 4.463  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 0.562  ops/ms
ClientPb.createUser                       avgt       3   3.087 ± 0.419   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 0.798   ms/op
ClientPb.getUser                          avgt       3   3.228 ± 1.430   ms/op
ClientPb.listUser                         avgt       3   3.774 ± 0.770   ms/op
ClientPb.createUser                     sample  304635   3.152 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.812           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.085           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.606           ms/op
ClientPb.existUser                      sample  307322   3.123 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.981           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.576           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.725           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706           ms/op
ClientPb.getUser                        sample  296149   3.241 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.220           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.381           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  260034   3.693 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.890           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.546           ms/op
