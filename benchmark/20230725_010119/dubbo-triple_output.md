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
# Warmup Iteration   1: 2.185 ops/ms
# Warmup Iteration   2: 5.983 ops/ms
# Warmup Iteration   3: 8.062 ops/ms
Iteration   1: 9.093 ops/ms
Iteration   2: 9.354 ops/ms
Iteration   3: 9.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.297 ±(99.9%) 3.318 ops/ms [Average]
  (min, avg, max) = (9.093, 9.297, 9.443), stdev = 0.182
  CI (99.9%): [5.979, 12.614] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 8.594 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.870 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.935 ±(99.9%) 1.991 ops/ms [Average]
  (min, avg, max) = (9.870, 9.935, 10.061), stdev = 0.109
  CI (99.9%): [7.944, 11.926] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.028 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 9.495 ops/ms
Iteration   2: 9.462 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.516 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (9.462, 9.516, 9.592), stdev = 0.068
  CI (99.9%): [8.284, 10.749] (assumes normal distribution)


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
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 7.143 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.052 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (8.003, 8.052, 8.130), stdev = 0.068
  CI (99.9%): [6.808, 9.297] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.677 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.007 ms/op
Iteration   1: 3.494 ±(99.9%) 0.005 ms/op
Iteration   2: 3.412 ±(99.9%) 0.007 ms/op
Iteration   3: 3.428 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.412, 3.445, 3.494), stdev = 0.043
  CI (99.9%): [2.656, 4.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.566 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.006 ms/op
Iteration   1: 3.342 ±(99.9%) 0.006 ms/op
Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
Iteration   3: 3.325 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (3.325, 3.332, 3.342), stdev = 0.009
  CI (99.9%): [3.170, 3.495] (assumes normal distribution)


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
# Warmup Iteration   1: 8.757 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.003 ms/op
Iteration   1: 3.450 ±(99.9%) 0.004 ms/op
Iteration   2: 3.541 ±(99.9%) 0.007 ms/op
Iteration   3: 3.456 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (3.450, 3.482, 3.541), stdev = 0.051
  CI (99.9%): [2.549, 4.416] (assumes normal distribution)


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
# Warmup Iteration   1: 9.979 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 3.893 ±(99.9%) 0.014 ms/op
Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
Iteration   3: 3.950 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.947 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (3.893, 3.947, 3.999), stdev = 0.053
  CI (99.9%): [2.980, 4.914] (assumes normal distribution)


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
# Warmup Iteration   1: 10.204 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
Iteration   1: 3.719 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.750 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  20.787 ms/op
                 createUser·p0.9999: 24.904 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  21.360 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274477
  mean =      3.498 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7843 
    [ 2.500,  5.000) = 251363 
    [ 5.000,  7.500) = 13614 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     26.021 ms/op
     p(99.9990) =     27.116 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.422 ms/op
                 existUser·p0.999:  13.546 ms/op
                 existUser·p0.9999: 24.867 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298870
  mean =      3.211 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3968 
    [ 2.500,  5.000) = 291284 
    [ 5.000,  7.500) = 2697 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     23.313 ms/op
     p(99.9990) =     25.363 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 9.563 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
Iteration   1: 3.543 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  13.850 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  21.064 ms/op
                 getUser·p0.9999: 28.647 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 24.696 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277467
  mean =      3.457 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6787 
    [ 2.500,  5.000) = 261736 
    [ 5.000,  7.500) = 7806 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     24.814 ms/op
     p(99.9990) =     29.244 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 12.500 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.012 ms/op
Iteration   1: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 22.385 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 4.120 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 20.937 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.005 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 20.615 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236228
  mean =      4.061 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 228467 
    [ 5.000,  7.500) = 5274 
    [ 7.500, 10.000) = 1690 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     16.802 ms/op
     p(99.9900) =     21.606 ms/op
     p(99.9990) =     23.632 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.297 ± 3.318  ops/ms
ClientPb.existUser                       thrpt       3   9.935 ± 1.991  ops/ms
ClientPb.getUser                         thrpt       3   9.516 ± 1.233  ops/ms
ClientPb.listUser                        thrpt       3   8.052 ± 1.245  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 0.789   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 0.933   ms/op
ClientPb.listUser                         avgt       3   3.947 ± 0.967   ms/op
ClientPb.createUser                     sample  274477   3.498 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.618           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.021           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  298870   3.211 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.461           ms/op
ClientPb.getUser                        sample  277467   3.457 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.814           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.426           ms/op
ClientPb.listUser                       sample  236228   4.061 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.235           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.802           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.606           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.790           ms/op
