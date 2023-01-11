# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.716 ops/ms
# Warmup Iteration   2: 6.361 ops/ms
# Warmup Iteration   3: 9.464 ops/ms
Iteration   1: 9.923 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 2.677 ops/ms [Average]
  (min, avg, max) = (9.636, 9.797, 9.923), stdev = 0.147
  CI (99.9%): [7.120, 12.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ops/ms
# Warmup Iteration   2: 9.645 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.457 ±(99.9%) 3.307 ops/ms [Average]
  (min, avg, max) = (10.249, 10.457, 10.584), stdev = 0.181
  CI (99.9%): [7.150, 13.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 9.259 ops/ms
# Warmup Iteration   3: 9.685 ops/ms
Iteration   1: 10.268 ops/ms
Iteration   2: 10.219 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.134 ±(99.9%) 3.486 ops/ms [Average]
  (min, avg, max) = (9.915, 10.134, 10.268), stdev = 0.191
  CI (99.9%): [6.648, 13.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ops/ms
# Warmup Iteration   2: 7.758 ops/ms
# Warmup Iteration   3: 8.311 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.583 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 4.408 ops/ms [Average]
  (min, avg, max) = (8.294, 8.550, 8.774), stdev = 0.242
  CI (99.9%): [4.143, 12.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.004 ms/op
Iteration   1: 3.149 ±(99.9%) 0.005 ms/op
Iteration   2: 3.284 ±(99.9%) 0.004 ms/op
Iteration   3: 3.109 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.180 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (3.109, 3.180, 3.284), stdev = 0.092
  CI (99.9%): [1.508, 4.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.394 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.005 ms/op
Iteration   1: 3.093 ±(99.9%) 0.004 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.046 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.016, 3.046, 3.093), stdev = 0.042
  CI (99.9%): [2.287, 3.805] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.122 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.004 ms/op
Iteration   1: 3.220 ±(99.9%) 0.004 ms/op
Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
Iteration   3: 3.075 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.184 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (3.075, 3.184, 3.257), stdev = 0.096
  CI (99.9%): [1.436, 4.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.006 ms/op
Iteration   1: 3.673 ±(99.9%) 0.005 ms/op
Iteration   2: 3.650 ±(99.9%) 0.009 ms/op
Iteration   3: 3.779 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.650, 3.701, 3.779), stdev = 0.069
  CI (99.9%): [2.440, 4.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.447 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 20.533 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.701 ms/op
                 createUser·p0.9999: 20.793 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   3: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  16.171 ms/op
                 createUser·p0.9999: 21.095 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 310531
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18015 
    [ 2.500,  5.000) = 288514 
    [ 5.000,  7.500) = 3045 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     16.021 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     21.554 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.421 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 19.113 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.172 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  17.138 ms/op
                 existUser·p0.9999: 22.214 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.193 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  13.538 ms/op
                 existUser·p0.9999: 20.446 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307939
  mean =      3.115 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18431 
    [ 2.500,  5.000) = 284293 
    [ 5.000,  7.500) = 3999 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     21.182 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.509 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.010 ms/op
Iteration   1: 3.260 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  10.527 ms/op
                 getUser·p0.9999: 22.485 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  13.101 ms/op
                 getUser·p0.9999: 23.503 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  12.545 ms/op
                 getUser·p0.9999: 22.742 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297222
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23813 
    [ 2.500,  5.000) = 265229 
    [ 5.000,  7.500) = 7044 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     12.825 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     24.022 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.883 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.011 ms/op
Iteration   1: 3.661 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.068 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  13.810 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.688 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.247 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259168
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 251797 
    [ 5.000,  7.500) = 5473 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     21.793 ms/op
     p(99.9990) =     24.387 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 2.677  ops/ms
ClientPb.existUser                       thrpt       3  10.457 ± 3.307  ops/ms
ClientPb.getUser                         thrpt       3  10.134 ± 3.486  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 4.408  ops/ms
ClientPb.createUser                       avgt       3   3.180 ± 1.673   ms/op
ClientPb.existUser                        avgt       3   3.046 ± 0.759   ms/op
ClientPb.getUser                          avgt       3   3.184 ± 1.748   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 1.261   ms/op
ClientPb.createUser                     sample  310531   3.091 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.775           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.725           ms/op
ClientPb.existUser                      sample  307939   3.115 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.905           ms/op
ClientPb.getUser                        sample  297222   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.774           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  259168   3.701 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.793           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
