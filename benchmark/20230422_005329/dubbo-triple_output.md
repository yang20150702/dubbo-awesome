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
# Warmup Iteration   2: 2.347 ops/ms
# Warmup Iteration   3: 5.050 ops/ms
Iteration   1: 5.237 ops/ms
Iteration   2: 5.634 ops/ms
Iteration   3: 5.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.472 ±(99.9%) 3.794 ops/ms [Average]
  (min, avg, max) = (5.237, 5.472, 5.634), stdev = 0.208
  CI (99.9%): [1.678, 9.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 5.744 ops/ms
Iteration   1: 6.013 ops/ms
Iteration   2: 5.996 ops/ms
Iteration   3: 5.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.999 ±(99.9%) 0.217 ops/ms [Average]
  (min, avg, max) = (5.989, 5.999, 6.013), stdev = 0.012
  CI (99.9%): [5.782, 6.217] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.465 ops/ms
# Warmup Iteration   2: 4.591 ops/ms
# Warmup Iteration   3: 5.525 ops/ms
Iteration   1: 5.504 ops/ms
Iteration   2: 5.642 ops/ms
Iteration   3: 5.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.698 ±(99.9%) 4.137 ops/ms [Average]
  (min, avg, max) = (5.504, 5.698, 5.947), stdev = 0.227
  CI (99.9%): [1.561, 9.835] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 3.829 ops/ms
# Warmup Iteration   3: 5.004 ops/ms
Iteration   1: 4.764 ops/ms
Iteration   2: 4.846 ops/ms
Iteration   3: 4.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.785 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (4.746, 4.785, 4.846), stdev = 0.054
  CI (99.9%): [3.807, 5.764] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.984 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.990 ±(99.9%) 0.013 ms/op
Iteration   1: 5.417 ±(99.9%) 0.018 ms/op
Iteration   2: 5.564 ±(99.9%) 0.017 ms/op
Iteration   3: 5.551 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.511 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (5.417, 5.511, 5.564), stdev = 0.081
  CI (99.9%): [4.028, 6.994] (assumes normal distribution)


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
# Warmup Iteration   1: 16.161 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.014 ms/op
Iteration   1: 5.219 ±(99.9%) 0.012 ms/op
Iteration   2: 5.281 ±(99.9%) 0.008 ms/op
Iteration   3: 5.254 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.251 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (5.219, 5.251, 5.281), stdev = 0.031
  CI (99.9%): [4.684, 5.818] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.409 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.174 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.020 ms/op
Iteration   1: 5.824 ±(99.9%) 0.009 ms/op
Iteration   2: 5.701 ±(99.9%) 0.014 ms/op
Iteration   3: 5.462 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.662 ±(99.9%) 3.364 ms/op [Average]
  (min, avg, max) = (5.462, 5.662, 5.824), stdev = 0.184
  CI (99.9%): [2.298, 9.026] (assumes normal distribution)


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
# Warmup Iteration   1: 19.951 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 9.016 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.569 ±(99.9%) 0.022 ms/op
Iteration   1: 6.465 ±(99.9%) 0.018 ms/op
Iteration   2: 6.353 ±(99.9%) 0.022 ms/op
Iteration   3: 6.060 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.293 ±(99.9%) 3.812 ms/op [Average]
  (min, avg, max) = (6.060, 6.293, 6.465), stdev = 0.209
  CI (99.9%): [2.481, 10.104] (assumes normal distribution)


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
# Warmup Iteration   1: 17.839 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.145 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.186 ±(99.9%) 0.027 ms/op
Iteration   1: 5.602 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.733 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  22.746 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   2: 5.556 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.520 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  29.702 ms/op
                 createUser·p0.9999: 36.378 ms/op
                 createUser·p1.00:   38.928 ms/op

Iteration   3: 5.644 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  13.271 ms/op
                 createUser·p0.9999: 28.748 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171384
  mean =      5.601 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 55576 
    [ 5.000,  7.500) = 106459 
    [ 7.500, 10.000) = 7651 
    [10.000, 12.500) = 1157 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     18.272 ms/op
     p(99.9900) =     34.616 ms/op
     p(99.9990) =     38.227 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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
# Warmup Iteration   1: 16.781 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.328 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.209 ±(99.9%) 0.017 ms/op
Iteration   1: 5.231 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   9.646 ms/op
                 existUser·p0.999:  25.285 ms/op
                 existUser·p0.9999: 27.816 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 5.475 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.404 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.332 ms/op
                 existUser·p0.99:   10.132 ms/op
                 existUser·p0.999:  18.186 ms/op
                 existUser·p0.9999: 27.760 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   3: 5.448 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.456 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  27.492 ms/op
                 existUser·p0.9999: 36.838 ms/op
                 existUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178337
  mean =      5.383 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 76920 
    [ 5.000,  7.500) = 93115 
    [ 7.500, 10.000) = 6698 
    [10.000, 12.500) = 1104 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     33.167 ms/op
     p(99.9990) =     39.130 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.365 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.566 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.813 ±(99.9%) 0.021 ms/op
Iteration   1: 5.585 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   7.848 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  24.427 ms/op
                 getUser·p0.9999: 28.916 ms/op
                 getUser·p1.00:   32.211 ms/op

Iteration   2: 5.602 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.637 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  16.548 ms/op
                 getUser·p0.9999: 34.931 ms/op
                 getUser·p1.00:   37.945 ms/op

Iteration   3: 5.279 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.863 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.233 ms/op
                 getUser·p0.999:  25.233 ms/op
                 getUser·p0.9999: 30.405 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174841
  mean =      5.484 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 62082 
    [ 5.000,  7.500) = 103750 
    [ 7.500, 10.000) = 7281 
    [10.000, 12.500) = 1206 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =      9.971 ms/op
     p(99.9000) =     18.650 ms/op
     p(99.9900) =     33.757 ms/op
     p(99.9990) =     37.847 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 20.038 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.390 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.689 ±(99.9%) 0.023 ms/op
Iteration   1: 6.844 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.166 ms/op
                 listUser·p0.50:   6.611 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  25.665 ms/op
                 listUser·p0.9999: 31.860 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 6.577 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.002 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  24.969 ms/op
                 listUser·p0.9999: 27.584 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   3: 6.450 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.294 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  26.851 ms/op
                 listUser·p0.9999: 29.722 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144946
  mean =      6.620 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3338 
    [ 5.000,  7.500) = 123006 
    [ 7.500, 10.000) = 15078 
    [10.000, 12.500) = 2619 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      6.398 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     26.018 ms/op
     p(99.9900) =     30.000 ms/op
     p(99.9990) =     32.209 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.472 ± 3.794  ops/ms
ClientPb.existUser                       thrpt       3   5.999 ± 0.217  ops/ms
ClientPb.getUser                         thrpt       3   5.698 ± 4.137  ops/ms
ClientPb.listUser                        thrpt       3   4.785 ± 0.978  ops/ms
ClientPb.createUser                       avgt       3   5.511 ± 1.483   ms/op
ClientPb.existUser                        avgt       3   5.251 ± 0.567   ms/op
ClientPb.getUser                          avgt       3   5.662 ± 3.364   ms/op
ClientPb.listUser                         avgt       3   6.293 ± 3.812   ms/op
ClientPb.createUser                     sample  171384   5.601 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.187           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.602           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.961           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.272           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.616           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.928           ms/op
ClientPb.existUser                      sample  178337   5.383 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.265           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.389           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.847           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.219           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.167           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.387           ms/op
ClientPb.getUser                        sample  174841   5.484 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.757           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.945           ms/op
ClientPb.listUser                       sample  144946   6.620 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.534           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.018           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.342           ms/op
