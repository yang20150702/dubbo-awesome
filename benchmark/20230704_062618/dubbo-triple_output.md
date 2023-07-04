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
# Warmup Iteration   1: 2.468 ops/ms
# Warmup Iteration   2: 5.883 ops/ms
# Warmup Iteration   3: 9.252 ops/ms
Iteration   1: 9.819 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.924 ±(99.9%) 6.610 ops/ms [Average]
  (min, avg, max) = (9.626, 9.924, 10.328), stdev = 0.362
  CI (99.9%): [3.314, 16.534] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.345 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.352 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (10.269, 10.352, 10.443), stdev = 0.087
  CI (99.9%): [8.762, 11.943] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.384 ops/ms
# Warmup Iteration   2: 8.180 ops/ms
# Warmup Iteration   3: 9.452 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.130 ±(99.9%) 3.185 ops/ms [Average]
  (min, avg, max) = (9.969, 10.130, 10.315), stdev = 0.175
  CI (99.9%): [6.945, 13.315] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.238 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.357 ops/ms
Iteration   3: 8.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.543 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (8.357, 8.543, 8.680), stdev = 0.167
  CI (99.9%): [5.496, 11.590] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.006 ms/op
Iteration   1: 3.242 ±(99.9%) 0.003 ms/op
Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
Iteration   3: 3.114 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.151 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.097, 3.151, 3.242), stdev = 0.079
  CI (99.9%): [1.701, 4.601] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.849 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.002 ms/op
Iteration   1: 3.178 ±(99.9%) 0.005 ms/op
Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.124 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.092, 3.124, 3.178), stdev = 0.047
  CI (99.9%): [2.268, 3.981] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.359 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.166 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.145, 3.166, 3.198), stdev = 0.028
  CI (99.9%): [2.653, 3.680] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.456 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.005 ms/op
Iteration   1: 3.707 ±(99.9%) 0.008 ms/op
Iteration   2: 3.687 ±(99.9%) 0.010 ms/op
Iteration   3: 3.693 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.687, 3.696, 3.707), stdev = 0.010
  CI (99.9%): [3.507, 3.884] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.150 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  18.325 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   4.171 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  21.987 ms/op
                 createUser·p0.9999: 27.045 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.310 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 18.523 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293739
  mean =      3.270 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23699 
    [ 2.500,  5.000) = 262860 
    [ 5.000,  7.500) = 6585 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.840 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  16.752 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 20.837 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  12.296 ms/op
                 existUser·p0.9999: 17.129 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310578
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24786 
    [ 2.500,  5.000) = 281304 
    [ 5.000,  7.500) = 3610 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     13.463 ms/op
     p(99.9900) =     20.249 ms/op
     p(99.9990) =     21.344 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 7.749 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.293 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 22.687 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.944 ms/op
                 getUser·p0.999:  17.847 ms/op
                 getUser·p0.9999: 22.646 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  9.364 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293715
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16488 
    [ 2.500,  5.000) = 270972 
    [ 5.000,  7.500) = 5323 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     24.629 ms/op
     p(99.9990) =     26.219 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 9.204 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
Iteration   1: 3.814 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 18.829 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  14.488 ms/op
                 listUser·p0.9999: 16.226 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.031 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 19.153 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250158
  mean =      3.835 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 239599 
    [ 5.000,  7.500) = 7351 
    [ 7.500, 10.000) = 2302 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.924 ± 6.610  ops/ms
ClientPb.existUser                       thrpt       3  10.352 ± 1.590  ops/ms
ClientPb.getUser                         thrpt       3  10.130 ± 3.185  ops/ms
ClientPb.listUser                        thrpt       3   8.543 ± 3.047  ops/ms
ClientPb.createUser                       avgt       3   3.151 ± 1.450   ms/op
ClientPb.existUser                        avgt       3   3.124 ± 0.857   ms/op
ClientPb.getUser                          avgt       3   3.166 ± 0.514   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 0.189   ms/op
ClientPb.createUser                     sample  293739   3.270 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.089           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.722           ms/op
ClientPb.existUser                      sample  310578   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.483           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.463           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.249           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.594           ms/op
ClientPb.getUser                        sample  293715   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.293           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.629           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  250158   3.835 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.372           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.349           ms/op
