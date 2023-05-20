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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 4.895 ops/ms
# Warmup Iteration   3: 8.795 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.244 ops/ms
Iteration   3: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.239 ±(99.9%) 0.083 ops/ms [Average]
  (min, avg, max) = (9.236, 9.239, 9.244), stdev = 0.005
  CI (99.9%): [9.156, 9.322] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.962 ops/ms
# Warmup Iteration   2: 8.720 ops/ms
# Warmup Iteration   3: 9.700 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 10.025 ops/ms
Iteration   3: 9.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.923 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (9.781, 9.923, 10.025), stdev = 0.127
  CI (99.9%): [7.608, 12.238] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.676 ops/ms
# Warmup Iteration   2: 8.315 ops/ms
# Warmup Iteration   3: 8.664 ops/ms
Iteration   1: 9.172 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.270 ±(99.9%) 3.171 ops/ms [Average]
  (min, avg, max) = (9.166, 9.270, 9.470), stdev = 0.174
  CI (99.9%): [6.099, 12.440] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.652 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 7.986 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (7.986, 8.097, 8.163), stdev = 0.096
  CI (99.9%): [6.337, 9.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.740 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
Iteration   1: 3.361 ±(99.9%) 0.011 ms/op
Iteration   2: 3.429 ±(99.9%) 0.007 ms/op
Iteration   3: 3.242 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.344 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (3.242, 3.344, 3.429), stdev = 0.095
  CI (99.9%): [1.610, 5.078] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.391 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.006 ms/op
Iteration   1: 3.306 ±(99.9%) 0.007 ms/op
Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
Iteration   3: 3.199 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (3.199, 3.284, 3.347), stdev = 0.077
  CI (99.9%): [1.886, 4.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.719 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.005 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.389 ±(99.9%) 0.005 ms/op
Iteration   3: 3.496 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.389, 3.428, 3.496), stdev = 0.059
  CI (99.9%): [2.345, 4.510] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.635 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.949 ±(99.9%) 0.008 ms/op
Iteration   2: 3.998 ±(99.9%) 0.009 ms/op
Iteration   3: 3.881 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.943 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.881, 3.943, 3.998), stdev = 0.058
  CI (99.9%): [2.877, 5.008] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.070 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  19.982 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  23.212 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  16.346 ms/op
                 createUser·p0.9999: 24.067 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282538
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11901 
    [ 2.500,  5.000) = 264759 
    [ 5.000,  7.500) = 4894 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     16.713 ms/op
     p(99.9900) =     25.755 ms/op
     p(99.9990) =     27.249 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.284 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  14.126 ms/op
                 existUser·p0.9999: 22.810 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.328 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  10.025 ms/op
                 existUser·p0.9999: 23.619 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  15.888 ms/op
                 existUser·p0.9999: 25.599 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290170
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17340 
    [ 2.500,  5.000) = 267090 
    [ 5.000,  7.500) = 4750 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.280 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     27.040 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.095 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
Iteration   1: 3.512 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  21.627 ms/op
                 getUser·p0.9999: 23.982 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  22.148 ms/op
                 getUser·p0.9999: 27.253 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.003 ms/op
                 getUser·p0.999:  20.384 ms/op
                 getUser·p0.9999: 27.575 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279146
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7355 
    [ 2.500,  5.000) = 264357 
    [ 5.000,  7.500) = 6386 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     27.233 ms/op
     p(99.9990) =     28.170 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.872 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.011 ms/op
Iteration   1: 4.013 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  17.339 ms/op
                 listUser·p0.9999: 23.299 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  15.915 ms/op
                 listUser·p0.9999: 18.984 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.818 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.407 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245078
  mean =      3.914 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 238456 
    [ 5.000,  7.500) = 4253 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.698 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.239 ± 0.083  ops/ms
ClientPb.existUser                       thrpt       3   9.923 ± 2.315  ops/ms
ClientPb.getUser                         thrpt       3   9.270 ± 3.171  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 1.760  ops/ms
ClientPb.createUser                       avgt       3   3.344 ± 1.734   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 1.398   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 1.082   ms/op
ClientPb.listUser                         avgt       3   3.943 ± 1.066   ms/op
ClientPb.createUser                     sample  282538   3.398 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.425           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  290170   3.305 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.280           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.642           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  279146   3.437 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.309           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.233           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  245078   3.914 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.692           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
