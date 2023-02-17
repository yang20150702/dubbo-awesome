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
# Warmup Iteration   1: 2.431 ops/ms
# Warmup Iteration   2: 6.129 ops/ms
# Warmup Iteration   3: 9.071 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 9.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.698 ±(99.9%) 5.444 ops/ms [Average]
  (min, avg, max) = (9.354, 9.698, 9.892), stdev = 0.298
  CI (99.9%): [4.254, 15.142] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 9.271 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.359 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (10.304, 10.359, 10.432), stdev = 0.065
  CI (99.9%): [9.165, 11.553] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 9.068 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.989 ±(99.9%) 3.950 ops/ms [Average]
  (min, avg, max) = (9.781, 9.989, 10.213), stdev = 0.217
  CI (99.9%): [6.040, 13.939] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ops/ms
# Warmup Iteration   2: 7.729 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.466 ops/ms
Iteration   2: 8.670 ops/ms
Iteration   3: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.624 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (8.466, 8.624, 8.736), stdev = 0.141
  CI (99.9%): [6.052, 11.196] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.952 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.003 ms/op
Iteration   1: 3.165 ±(99.9%) 0.004 ms/op
Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
Iteration   3: 3.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (3.119, 3.181, 3.258), stdev = 0.071
  CI (99.9%): [1.886, 4.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.638 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.005 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
Iteration   3: 3.262 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.157 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.099, 3.157, 3.262), stdev = 0.091
  CI (99.9%): [1.501, 4.813] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.002 ms/op
Iteration   1: 3.140 ±(99.9%) 0.005 ms/op
Iteration   2: 3.356 ±(99.9%) 0.004 ms/op
Iteration   3: 3.224 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.240 ±(99.9%) 1.977 ms/op [Average]
  (min, avg, max) = (3.140, 3.240, 3.356), stdev = 0.108
  CI (99.9%): [1.263, 5.217] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.473 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.010 ms/op
Iteration   1: 3.746 ±(99.9%) 0.006 ms/op
Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
Iteration   3: 3.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.792 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.746, 3.792, 3.867), stdev = 0.066
  CI (99.9%): [2.588, 4.996] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.992 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.197 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  11.811 ms/op
                 createUser·p0.9999: 21.397 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.137 ms/op
                 createUser·p0.9999: 22.686 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  14.499 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296410
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12154 
    [ 2.500,  5.000) = 278592 
    [ 5.000,  7.500) = 4734 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     23.048 ms/op
     p(99.9990) =     24.290 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.475 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  10.994 ms/op
                 existUser·p0.9999: 22.119 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.524 ms/op
                 existUser·p0.9999: 21.622 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  14.320 ms/op
                 existUser·p0.9999: 20.122 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300444
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31130 
    [ 2.500,  5.000) = 263096 
    [ 5.000,  7.500) = 5496 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     12.859 ms/op
     p(99.9900) =     21.493 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.294 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.254 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  11.125 ms/op
                 getUser·p0.9999: 17.733 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.971 ms/op
                 getUser·p0.999:  12.983 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.219 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.063 ms/op
                 getUser·p0.9999: 35.329 ms/op
                 getUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299353
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17630 
    [ 2.500,  5.000) = 275379 
    [ 5.000,  7.500) = 5333 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     16.182 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 9.728 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
Iteration   1: 3.713 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.688 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 30.470 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 3.751 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 15.810 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.617 ms/op
                 listUser·p0.999:  13.887 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252925
  mean =      3.795 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 243723 
    [ 5.000,  7.500) = 7226 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     29.716 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.698 ± 5.444  ops/ms
ClientPb.existUser                       thrpt       3  10.359 ± 1.194  ops/ms
ClientPb.getUser                         thrpt       3   9.989 ± 3.950  ops/ms
ClientPb.listUser                        thrpt       3   8.624 ± 2.572  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.295   ms/op
ClientPb.existUser                        avgt       3   3.157 ± 1.656   ms/op
ClientPb.getUser                          avgt       3   3.240 ± 1.977   ms/op
ClientPb.listUser                         avgt       3   3.792 ± 1.204   ms/op
ClientPb.createUser                     sample  296410   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.056           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.048           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.969           ms/op
ClientPb.existUser                      sample  300444   3.196 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.957           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.859           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.493           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  299353   3.204 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.950           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.182           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.372           ms/op
ClientPb.listUser                       sample  252925   3.795 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.135           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.716           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.769           ms/op
