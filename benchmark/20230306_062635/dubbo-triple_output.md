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
# Warmup Iteration   1: 1.109 ops/ms
# Warmup Iteration   2: 2.415 ops/ms
# Warmup Iteration   3: 5.236 ops/ms
Iteration   1: 5.945 ops/ms
Iteration   2: 6.018 ops/ms
Iteration   3: 6.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.142 ±(99.9%) 5.110 ops/ms [Average]
  (min, avg, max) = (5.945, 6.142, 6.463), stdev = 0.280
  CI (99.9%): [1.032, 11.252] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.600 ops/ms
# Warmup Iteration   2: 5.180 ops/ms
# Warmup Iteration   3: 6.253 ops/ms
Iteration   1: 6.246 ops/ms
Iteration   2: 6.756 ops/ms
Iteration   3: 6.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.566 ±(99.9%) 5.083 ops/ms [Average]
  (min, avg, max) = (6.246, 6.566, 6.756), stdev = 0.279
  CI (99.9%): [1.483, 11.648] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.772 ops/ms
# Warmup Iteration   2: 5.058 ops/ms
# Warmup Iteration   3: 5.819 ops/ms
Iteration   1: 5.920 ops/ms
Iteration   2: 6.126 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.984 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (5.907, 5.984, 6.126), stdev = 0.123
  CI (99.9%): [3.747, 8.221] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 4.420 ops/ms
# Warmup Iteration   3: 5.303 ops/ms
Iteration   1: 5.387 ops/ms
Iteration   2: 5.477 ops/ms
Iteration   3: 5.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.341 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (5.159, 5.341, 5.477), stdev = 0.164
  CI (99.9%): [2.355, 8.327] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.175 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.386 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.010 ms/op
Iteration   1: 5.349 ±(99.9%) 0.009 ms/op
Iteration   2: 5.392 ±(99.9%) 0.010 ms/op
Iteration   3: 5.290 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.344 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (5.290, 5.344, 5.392), stdev = 0.051
  CI (99.9%): [4.416, 6.271] (assumes normal distribution)


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
# Warmup Iteration   1: 15.694 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.706 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.106 ±(99.9%) 0.006 ms/op
Iteration   1: 5.287 ±(99.9%) 0.015 ms/op
Iteration   2: 5.068 ±(99.9%) 0.023 ms/op
Iteration   3: 5.001 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.119 ±(99.9%) 2.730 ms/op [Average]
  (min, avg, max) = (5.001, 5.119, 5.287), stdev = 0.150
  CI (99.9%): [2.389, 7.849] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.110 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.128 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.116 ±(99.9%) 0.018 ms/op
Iteration   1: 5.229 ±(99.9%) 0.022 ms/op
Iteration   2: 5.269 ±(99.9%) 0.014 ms/op
Iteration   3: 5.226 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.241 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (5.226, 5.241, 5.269), stdev = 0.024
  CI (99.9%): [4.808, 5.675] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.943 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 7.595 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.971 ±(99.9%) 0.017 ms/op
Iteration   1: 6.129 ±(99.9%) 0.018 ms/op
Iteration   2: 6.145 ±(99.9%) 0.009 ms/op
Iteration   3: 5.899 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.058 ±(99.9%) 2.507 ms/op [Average]
  (min, avg, max) = (5.899, 6.058, 6.145), stdev = 0.137
  CI (99.9%): [3.551, 8.565] (assumes normal distribution)


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
# Warmup Iteration   1: 16.312 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.318 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.725 ±(99.9%) 0.024 ms/op
Iteration   1: 5.428 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  22.675 ms/op
                 createUser·p0.9999: 26.104 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   2: 5.308 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  24.591 ms/op
                 createUser·p0.9999: 28.110 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 5.152 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   6.955 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  23.098 ms/op
                 createUser·p0.9999: 28.605 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181349
  mean =      5.293 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 91996 
    [ 5.000,  7.500) = 80533 
    [ 7.500, 10.000) = 7309 
    [10.000, 12.500) = 1026 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     28.097 ms/op
     p(99.9990) =     29.215 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 15.514 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.849 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.347 ±(99.9%) 0.021 ms/op
Iteration   1: 5.262 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  22.428 ms/op
                 existUser·p0.9999: 28.241 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   2: 5.003 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   5.718 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  26.220 ms/op
                 existUser·p0.9999: 30.279 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 5.181 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 27.585 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186500
  mean =      5.147 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 105350 
    [ 5.000,  7.500) = 75162 
    [ 7.500, 10.000) = 4467 
    [10.000, 12.500) = 942 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.216 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     30.658 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.395 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 6.526 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.019 ms/op
Iteration   1: 5.253 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.466 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  15.145 ms/op
                 getUser·p0.9999: 30.436 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   2: 5.026 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  22.538 ms/op
                 getUser·p0.9999: 28.811 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 5.319 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  24.144 ms/op
                 getUser·p0.9999: 28.573 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184780
  mean =      5.196 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 104764 
    [ 5.000,  7.500) = 71776 
    [ 7.500, 10.000) = 6817 
    [10.000, 12.500) = 878 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     28.934 ms/op
     p(99.9990) =     30.681 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 17.803 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.951 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.995 ±(99.9%) 0.020 ms/op
Iteration   1: 6.111 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.904 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  27.001 ms/op
                 listUser·p0.9999: 30.945 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 5.795 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  24.929 ms/op
                 listUser·p0.9999: 31.654 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 6.081 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.879 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 26.820 ms/op
                 listUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160160
  mean =      5.992 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 13961 
    [ 5.000,  7.500) = 134653 
    [ 7.500, 10.000) = 8450 
    [10.000, 12.500) = 2074 
    [12.500, 15.000) = 558 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     25.390 ms/op
     p(99.9900) =     30.899 ms/op
     p(99.9990) =     32.106 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.142 ± 5.110  ops/ms
ClientPb.existUser                       thrpt       3   6.566 ± 5.083  ops/ms
ClientPb.getUser                         thrpt       3   5.984 ± 2.237  ops/ms
ClientPb.listUser                        thrpt       3   5.341 ± 2.986  ops/ms
ClientPb.createUser                       avgt       3   5.344 ± 0.928   ms/op
ClientPb.existUser                        avgt       3   5.119 ± 2.730   ms/op
ClientPb.getUser                          avgt       3   5.241 ± 0.434   ms/op
ClientPb.listUser                         avgt       3   6.058 ± 2.507   ms/op
ClientPb.createUser                     sample  181349   5.293 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.872           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  186500   5.147 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.216           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.388           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.721           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  184780   5.196 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.283           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.934           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  160160   5.992 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.572           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.390           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.899           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
