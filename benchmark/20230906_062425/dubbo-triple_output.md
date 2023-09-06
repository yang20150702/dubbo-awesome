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
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 5.939 ops/ms
# Warmup Iteration   3: 8.841 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.659 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (9.534, 9.659, 9.874), stdev = 0.187
  CI (99.9%): [6.242, 13.076] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 9.741 ops/ms
Iteration   1: 10.198 ops/ms
Iteration   2: 10.415 ops/ms
Iteration   3: 9.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.197 ±(99.9%) 3.984 ops/ms [Average]
  (min, avg, max) = (9.978, 10.197, 10.415), stdev = 0.218
  CI (99.9%): [6.213, 14.181] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 9.015 ops/ms
# Warmup Iteration   3: 9.367 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.804 ±(99.9%) 7.605 ops/ms [Average]
  (min, avg, max) = (9.421, 9.804, 10.248), stdev = 0.417
  CI (99.9%): [2.199, 17.410] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.379 ops/ms
Iteration   2: 8.408 ops/ms
Iteration   3: 8.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.439 ±(99.9%) 1.466 ops/ms [Average]
  (min, avg, max) = (8.379, 8.439, 8.530), stdev = 0.080
  CI (99.9%): [6.974, 9.905] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.766 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.005 ms/op
Iteration   1: 3.251 ±(99.9%) 0.004 ms/op
Iteration   2: 3.361 ±(99.9%) 0.007 ms/op
Iteration   3: 3.378 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.330 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.251, 3.330, 3.378), stdev = 0.069
  CI (99.9%): [2.072, 4.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.772 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.002 ms/op
Iteration   2: 3.154 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.106, 3.123, 3.154), stdev = 0.027
  CI (99.9%): [2.633, 3.613] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.083 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.004 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.295 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.211 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (3.130, 3.211, 3.295), stdev = 0.083
  CI (99.9%): [1.706, 4.717] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.001 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.008 ms/op
Iteration   1: 3.865 ±(99.9%) 0.006 ms/op
Iteration   2: 3.731 ±(99.9%) 0.005 ms/op
Iteration   3: 3.812 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.803 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (3.731, 3.803, 3.865), stdev = 0.068
  CI (99.9%): [2.571, 5.035] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.863 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  17.634 ms/op
                 createUser·p0.9999: 21.150 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 3.297 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.532 ms/op
                 createUser·p0.999:  20.186 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 18.314 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290583
  mean =      3.302 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19554 
    [ 2.500,  5.000) = 263365 
    [ 5.000,  7.500) = 6230 
    [ 7.500, 10.000) = 951 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     16.354 ms/op
     p(99.9900) =     22.835 ms/op
     p(99.9990) =     23.995 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 6.929 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  9.100 ms/op
                 existUser·p0.9999: 22.316 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.200 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  16.363 ms/op
                 existUser·p0.9999: 26.543 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299761
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20850 
    [ 2.500,  5.000) = 271847 
    [ 5.000,  7.500) = 5540 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     13.070 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     26.936 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.646 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.010 ms/op
Iteration   1: 3.288 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 24.005 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.317 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  16.568 ms/op
                 getUser·p0.9999: 29.580 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  10.019 ms/op
                 getUser·p0.9999: 23.332 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293430
  mean =      3.270 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19437 
    [ 2.500,  5.000) = 264847 
    [ 5.000,  7.500) = 7618 
    [ 7.500, 10.000) = 1164 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     30.319 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 8.688 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.013 ms/op
Iteration   1: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  13.098 ms/op
                 listUser·p0.9999: 24.762 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  13.329 ms/op
                 listUser·p0.9999: 17.778 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 19.412 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252625
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 242180 
    [ 5.000,  7.500) = 7777 
    [ 7.500, 10.000) = 1911 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     23.191 ms/op
     p(99.9990) =     25.782 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.659 ± 3.417  ops/ms
ClientPb.existUser                       thrpt       3  10.197 ± 3.984  ops/ms
ClientPb.getUser                         thrpt       3   9.804 ± 7.605  ops/ms
ClientPb.listUser                        thrpt       3   8.439 ± 1.466  ops/ms
ClientPb.createUser                       avgt       3   3.330 ± 1.258   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 0.490   ms/op
ClientPb.getUser                          avgt       3   3.211 ± 1.506   ms/op
ClientPb.listUser                         avgt       3   3.803 ± 1.232   ms/op
ClientPb.createUser                     sample  290583   3.302 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  299761   3.199 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.070           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.952           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  293430   3.270 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  252625   3.797 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.191           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
