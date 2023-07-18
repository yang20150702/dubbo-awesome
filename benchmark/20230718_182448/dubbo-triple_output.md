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
# Warmup Iteration   1: 2.180 ops/ms
# Warmup Iteration   2: 5.340 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.088 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 3.635 ops/ms [Average]
  (min, avg, max) = (9.088, 9.288, 9.486), stdev = 0.199
  CI (99.9%): [5.653, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 9.088 ops/ms
# Warmup Iteration   3: 9.428 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 5.116 ops/ms [Average]
  (min, avg, max) = (9.494, 9.801, 10.044), stdev = 0.280
  CI (99.9%): [4.685, 14.917] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.818 ops/ms
# Warmup Iteration   2: 8.492 ops/ms
# Warmup Iteration   3: 9.141 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 9.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 5.062 ops/ms [Average]
  (min, avg, max) = (9.056, 9.245, 9.563), stdev = 0.277
  CI (99.9%): [4.183, 14.307] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.952 ops/ms
# Warmup Iteration   2: 7.021 ops/ms
# Warmup Iteration   3: 7.630 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 7.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.802 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (7.672, 7.802, 7.909), stdev = 0.120
  CI (99.9%): [5.607, 9.997] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.259 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.011 ms/op
Iteration   1: 3.397 ±(99.9%) 0.006 ms/op
Iteration   2: 3.416 ±(99.9%) 0.012 ms/op
Iteration   3: 3.393 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.402 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.393, 3.402, 3.416), stdev = 0.012
  CI (99.9%): [3.176, 3.628] (assumes normal distribution)


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
# Warmup Iteration   1: 8.408 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.006 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
Iteration   2: 3.358 ±(99.9%) 0.013 ms/op
Iteration   3: 3.342 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.275, 3.325, 3.358), stdev = 0.044
  CI (99.9%): [2.529, 4.121] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.009 ms/op
Iteration   1: 3.446 ±(99.9%) 0.005 ms/op
Iteration   2: 3.426 ±(99.9%) 0.006 ms/op
Iteration   3: 3.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.454 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.426, 3.454, 3.490), stdev = 0.033
  CI (99.9%): [2.858, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 9.926 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.965 ±(99.9%) 0.009 ms/op
Iteration   2: 3.998 ±(99.9%) 0.011 ms/op
Iteration   3: 3.827 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.930 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (3.827, 3.930, 3.998), stdev = 0.090
  CI (99.9%): [2.281, 5.579] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.722 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 23.481 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  18.950 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 21.987 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286619
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14229 
    [ 2.500,  5.000) = 264975 
    [ 5.000,  7.500) = 6526 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     16.215 ms/op
     p(99.9900) =     23.473 ms/op
     p(99.9990) =     25.826 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 9.677 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  15.676 ms/op
                 existUser·p0.9999: 23.592 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.009 ms/op
                 existUser·p0.9999: 25.074 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.632 ms/op
                 existUser·p0.95:   4.165 ms/op
                 existUser·p0.99:   5.901 ms/op
                 existUser·p0.999:  17.365 ms/op
                 existUser·p0.9999: 26.063 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290953
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4781 
    [ 2.500,  5.000) = 280984 
    [ 5.000,  7.500) = 4237 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     25.228 ms/op
     p(99.9990) =     26.387 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 9.134 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.009 ms/op
Iteration   1: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  19.777 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.364 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  22.146 ms/op
                 getUser·p0.9999: 36.045 ms/op
                 getUser·p1.00:   36.766 ms/op

Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  18.344 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282329
  mean =      3.400 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15514 
    [ 2.500,  5.000) = 259281 
    [ 5.000,  7.500) = 6187 
    [ 7.500, 10.000) = 916 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     18.536 ms/op
     p(99.9900) =     31.602 ms/op
     p(99.9990) =     36.319 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 9.483 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
Iteration   1: 3.956 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 24.043 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 3.965 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 16.253 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 3.998 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.359 ms/op
                 listUser·p0.999:  14.056 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241709
  mean =      3.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 234343 
    [ 5.000,  7.500) = 5369 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.160 ms/op
     p(99.9900) =     22.533 ms/op
     p(99.9990) =     24.530 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 3.635  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 5.116  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 5.062  ops/ms
ClientPb.listUser                        thrpt       3   7.802 ± 2.195  ops/ms
ClientPb.createUser                       avgt       3   3.402 ± 0.226   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 0.796   ms/op
ClientPb.getUser                          avgt       3   3.454 ± 0.596   ms/op
ClientPb.listUser                         avgt       3   3.930 ± 1.649   ms/op
ClientPb.createUser                     sample  286619   3.346 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.215           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.473           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.854           ms/op
ClientPb.existUser                      sample  290953   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.096           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.228           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  282329   3.400 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.247           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.602           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  241709   3.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.109           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.160           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.533           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
