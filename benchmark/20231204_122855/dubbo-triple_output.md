# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.069 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.619 ops/ms
Iteration   1: 12.701 ops/ms
Iteration   2: 12.830 ops/ms
Iteration   3: 12.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.802 ±(99.9%) 1.650 ops/ms [Average]
  (min, avg, max) = (12.701, 12.802, 12.875), stdev = 0.090
  CI (99.9%): [11.152, 14.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.073 ops/ms
# Warmup Iteration   2: 13.109 ops/ms
# Warmup Iteration   3: 13.150 ops/ms
Iteration   1: 13.181 ops/ms
Iteration   2: 13.165 ops/ms
Iteration   3: 13.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.183 ±(99.9%) 0.336 ops/ms [Average]
  (min, avg, max) = (13.165, 13.183, 13.202), stdev = 0.018
  CI (99.9%): [12.847, 13.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 13.014 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 13.126 ops/ms
Iteration   2: 13.310 ops/ms
Iteration   3: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.183 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (13.114, 13.183, 13.310), stdev = 0.110
  CI (99.9%): [11.174, 15.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 10.849 ops/ms
Iteration   2: 10.822 ops/ms
Iteration   3: 10.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.799 ±(99.9%) 1.189 ops/ms [Average]
  (min, avg, max) = (10.725, 10.799, 10.849), stdev = 0.065
  CI (99.9%): [9.610, 11.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.443 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (2.441, 2.443, 2.445), stdev = 0.003
  CI (99.9%): [2.397, 2.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.412, 2.417, 2.426), stdev = 0.008
  CI (99.9%): [2.267, 2.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.003 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.424 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.411, 2.424, 2.435), stdev = 0.012
  CI (99.9%): [2.200, 2.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.006 ms/op
Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
Iteration   3: 2.928 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.936 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.928, 2.936, 2.953), stdev = 0.015
  CI (99.9%): [2.670, 3.203] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  6.902 ms/op
                 createUser·p0.9999: 13.304 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  5.796 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  9.071 ms/op
                 createUser·p0.9999: 14.618 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388166
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 191079 
    [ 2.500,  3.750) = 193046 
    [ 3.750,  5.000) = 3245 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.354 ms/op
     p(99.9900) =     13.523 ms/op
     p(99.9990) =     14.813 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.271 ms/op
                 existUser·p0.9999: 13.555 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.495 ms/op
                 existUser·p0.999:  7.182 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 10.142 ms/op
                 existUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399662
  mean =      2.400 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 203308 
    [ 2.500,  3.750) = 193246 
    [ 3.750,  5.000) = 2247 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.294 ms/op
     p(99.9900) =     12.681 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  5.490 ms/op
                 getUser·p0.9999: 12.402 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  5.810 ms/op
                 getUser·p0.9999: 11.809 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393371
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 201314 
    [ 2.500,  3.750) = 188271 
    [ 3.750,  5.000) = 2905 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 159 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      5.854 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.436 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.002 ms/op
                 listUser·p0.9999: 12.772 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.479 ms/op
                 listUser·p0.9999: 11.698 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317384
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 93774 
    [ 2.500,  3.750) = 182400 
    [ 3.750,  5.000) = 32607 
    [ 5.000,  6.250) = 6863 
    [ 6.250,  7.500) = 895 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.702 ms/op
     p(99.9990) =     13.262 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.802 ± 1.650  ops/ms
ClientPb.existUser                       thrpt       3  13.183 ± 0.336  ops/ms
ClientPb.getUser                         thrpt       3  13.183 ± 2.009  ops/ms
ClientPb.listUser                        thrpt       3  10.799 ± 1.189  ops/ms
ClientPb.createUser                       avgt       3   2.443 ± 0.046   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.149   ms/op
ClientPb.getUser                          avgt       3   2.424 ± 0.224   ms/op
ClientPb.listUser                         avgt       3   2.936 ± 0.266   ms/op
ClientPb.createUser                     sample  388166   2.470 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.523           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  399662   2.400 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.767           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.294           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.681           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  393371   2.438 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.957           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.970           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.854           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.517           ms/op
ClientPb.listUser                       sample  317384   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.863           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.702           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
