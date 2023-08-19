# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 5.967 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 9.168 ops/ms
Iteration   2: 9.024 ops/ms
Iteration   3: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.068 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (9.013, 9.068, 9.168), stdev = 0.087
  CI (99.9%): [7.490, 10.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.637 ops/ms
Iteration   1: 9.817 ops/ms
Iteration   2: 9.766 ops/ms
Iteration   3: 9.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.788 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (9.766, 9.788, 9.817), stdev = 0.026
  CI (99.9%): [9.311, 10.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 8.048 ops/ms
# Warmup Iteration   3: 9.118 ops/ms
Iteration   1: 9.285 ops/ms
Iteration   2: 9.326 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.424 ±(99.9%) 3.771 ops/ms [Average]
  (min, avg, max) = (9.285, 9.424, 9.661), stdev = 0.207
  CI (99.9%): [5.653, 13.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.202 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 7.932 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.949 ±(99.9%) 0.282 ops/ms [Average]
  (min, avg, max) = (7.932, 7.949, 7.960), stdev = 0.015
  CI (99.9%): [7.667, 8.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.082 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.005 ms/op
Iteration   1: 3.492 ±(99.9%) 0.007 ms/op
Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
Iteration   3: 3.395 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.468 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.395, 3.468, 3.517), stdev = 0.064
  CI (99.9%): [2.292, 4.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.753 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.004 ms/op
Iteration   1: 3.386 ±(99.9%) 0.007 ms/op
Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
Iteration   3: 3.425 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.361 ±(99.9%) 1.457 ms/op [Average]
  (min, avg, max) = (3.271, 3.361, 3.425), stdev = 0.080
  CI (99.9%): [1.904, 4.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.587 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.005 ms/op
Iteration   1: 3.629 ±(99.9%) 0.004 ms/op
Iteration   2: 3.422 ±(99.9%) 0.008 ms/op
Iteration   3: 3.429 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.493 ±(99.9%) 2.141 ms/op [Average]
  (min, avg, max) = (3.422, 3.493, 3.629), stdev = 0.117
  CI (99.9%): [1.353, 5.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.228 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.008 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
Iteration   2: 4.054 ±(99.9%) 0.015 ms/op
Iteration   3: 4.172 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.069 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (3.982, 4.069, 4.172), stdev = 0.096
  CI (99.9%): [2.319, 5.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.305 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.574 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  17.732 ms/op
                 createUser·p0.9999: 34.341 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  18.064 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273988
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9213 
    [ 2.500,  5.000) = 255753 
    [ 5.000,  7.500) = 7303 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     30.972 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.009 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  11.122 ms/op
                 existUser·p0.9999: 22.190 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  20.123 ms/op
                 existUser·p0.9999: 28.738 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 3.377 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  18.826 ms/op
                 existUser·p0.9999: 26.953 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288318
  mean =      3.326 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3570 
    [ 2.500,  5.000) = 277327 
    [ 5.000,  7.500) = 5774 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     18.672 ms/op
     p(99.9900) =     27.438 ms/op
     p(99.9990) =     29.375 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.373 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.012 ms/op
Iteration   1: 3.542 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  14.764 ms/op
                 getUser·p0.9999: 21.920 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.657 ms/op
                 getUser·p0.999:  22.643 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  20.370 ms/op
                 getUser·p0.9999: 27.492 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273969
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7197 
    [ 2.500,  5.000) = 256568 
    [ 5.000,  7.500) = 8581 
    [ 7.500, 10.000) = 960 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 104 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.735 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.015 ms/op
Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  21.951 ms/op
                 listUser·p0.9999: 27.639 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  18.445 ms/op
                 listUser·p0.9999: 20.948 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  18.341 ms/op
                 listUser·p0.9999: 24.021 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234756
  mean =      4.085 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 224754 
    [ 5.000,  7.500) = 6790 
    [ 7.500, 10.000) = 2040 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     26.133 ms/op
     p(99.9990) =     28.453 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.068 ± 1.578  ops/ms
ClientPb.existUser                       thrpt       3   9.788 ± 0.477  ops/ms
ClientPb.getUser                         thrpt       3   9.424 ± 3.771  ops/ms
ClientPb.listUser                        thrpt       3   7.949 ± 0.282  ops/ms
ClientPb.createUser                       avgt       3   3.468 ± 1.176   ms/op
ClientPb.existUser                        avgt       3   3.361 ± 1.457   ms/op
ClientPb.getUser                          avgt       3   3.493 ± 2.141   ms/op
ClientPb.listUser                         avgt       3   4.069 ± 1.750   ms/op
ClientPb.createUser                     sample  273988   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.504           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  288318   3.326 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.672           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.438           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  273969   3.505 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.165           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.049           ms/op
ClientPb.listUser                       sample  234756   4.085 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.431           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
