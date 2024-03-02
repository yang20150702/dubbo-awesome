# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 11.860 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.628 ops/ms
Iteration   2: 12.829 ops/ms
Iteration   3: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.764 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (12.628, 12.764, 12.834), stdev = 0.118
  CI (99.9%): [10.615, 14.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.332 ops/ms
# Warmup Iteration   2: 13.267 ops/ms
# Warmup Iteration   3: 13.276 ops/ms
Iteration   1: 13.241 ops/ms
Iteration   2: 13.282 ops/ms
Iteration   3: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (13.190, 13.238, 13.282), stdev = 0.046
  CI (99.9%): [12.404, 14.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.688 ops/ms
# Warmup Iteration   2: 12.308 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.632 ops/ms
Iteration   3: 12.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.683 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (12.632, 12.683, 12.761), stdev = 0.069
  CI (99.9%): [11.429, 13.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.539 ops/ms
# Warmup Iteration   2: 10.332 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.585 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (10.497, 10.585, 10.633), stdev = 0.077
  CI (99.9%): [9.183, 11.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.003 ms/op
Iteration   3: 2.478 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.492 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (2.475, 2.492, 2.525), stdev = 0.028
  CI (99.9%): [1.978, 3.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
Iteration   2: 2.442 ±(99.9%) 0.002 ms/op
Iteration   3: 2.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.442, 2.451, 2.465), stdev = 0.012
  CI (99.9%): [2.232, 2.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.543 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (2.521, 2.543, 2.562), stdev = 0.021
  CI (99.9%): [2.163, 2.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.015 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.013, 3.028, 3.055), stdev = 0.024
  CI (99.9%): [2.594, 3.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  12.234 ms/op
                 createUser·p0.9999: 14.300 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  10.222 ms/op
                 createUser·p0.9999: 13.650 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 2.578 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.833 ms/op
                 createUser·p0.9999: 12.216 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373005
  mean =      2.570 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 177749 
    [ 2.500,  3.750) = 191496 
    [ 3.750,  5.000) = 2895 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.553 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.700 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  8.542 ms/op
                 existUser·p0.9999: 15.056 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.716 ms/op
                 existUser·p0.999:  5.977 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.590 ms/op
                 existUser·p0.999:  8.391 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392243
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 198561 
    [ 2.500,  3.750) = 189745 
    [ 3.750,  5.000) = 2908 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.691 ms/op
     p(99.9900) =     14.840 ms/op
     p(99.9990) =     15.846 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.642 ms/op
                 getUser·p0.999:  8.513 ms/op
                 getUser·p0.9999: 18.348 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  5.795 ms/op
                 getUser·p0.9999: 12.062 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  7.087 ms/op
                 getUser·p0.9999: 11.749 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389014
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 196617 
    [ 2.500,  3.750) = 187366 
    [ 3.750,  5.000) = 4036 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      6.939 ms/op
     p(99.9900) =     14.682 ms/op
     p(99.9990) =     18.619 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.456 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.605 ms/op
                 listUser·p0.9999: 11.052 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  10.076 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317027
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 89346 
    [ 2.500,  3.750) = 186452 
    [ 3.750,  5.000) = 33524 
    [ 5.000,  6.250) = 6219 
    [ 6.250,  7.500) = 693 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.469 ms/op
     p(99.9900) =     11.359 ms/op
     p(99.9990) =     12.551 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.764 ± 2.148  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 0.833  ops/ms
ClientPb.getUser                         thrpt       3  12.683 ± 1.254  ops/ms
ClientPb.listUser                        thrpt       3  10.585 ± 1.403  ops/ms
ClientPb.createUser                       avgt       3   2.492 ± 0.514   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.219   ms/op
ClientPb.getUser                          avgt       3   2.543 ± 0.380   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.434   ms/op
ClientPb.createUser                     sample  373005   2.570 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.588           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.892           ms/op
ClientPb.existUser                      sample  392243   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.930           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.691           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.840           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.991           ms/op
ClientPb.getUser                        sample  389014   2.466 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.633           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.939           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.682           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.711           ms/op
ClientPb.listUser                       sample  317027   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.947           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.469           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.359           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
