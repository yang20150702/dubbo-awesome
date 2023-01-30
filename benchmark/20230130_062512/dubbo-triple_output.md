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
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.530 ops/ms
Iteration   3: 9.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.552 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (9.530, 9.552, 9.563), stdev = 0.019
  CI (99.9%): [9.206, 9.897] (assumes normal distribution)


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
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.444 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.447 ±(99.9%) 3.622 ops/ms [Average]
  (min, avg, max) = (10.224, 10.447, 10.604), stdev = 0.199
  CI (99.9%): [6.825, 14.070] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ops/ms
# Warmup Iteration   2: 9.438 ops/ms
# Warmup Iteration   3: 9.374 ops/ms
Iteration   1: 10.028 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.878 ±(99.9%) 2.810 ops/ms [Average]
  (min, avg, max) = (9.720, 9.878, 10.028), stdev = 0.154
  CI (99.9%): [7.068, 12.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 8.052 ops/ms
# Warmup Iteration   3: 8.311 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.329 ±(99.9%) 3.113 ops/ms [Average]
  (min, avg, max) = (8.172, 8.329, 8.511), stdev = 0.171
  CI (99.9%): [5.216, 11.441] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.418 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.006 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
Iteration   2: 3.291 ±(99.9%) 0.005 ms/op
Iteration   3: 3.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.201 ±(99.9%) 2.062 ms/op [Average]
  (min, avg, max) = (3.074, 3.201, 3.291), stdev = 0.113
  CI (99.9%): [1.139, 5.263] (assumes normal distribution)


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
# Warmup Iteration   1: 6.971 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.011 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (2.986, 3.011, 3.048), stdev = 0.033
  CI (99.9%): [2.416, 3.606] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.225 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.212 ±(99.9%) 0.005 ms/op
Iteration   3: 3.223 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.256 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.212, 3.256, 3.332), stdev = 0.066
  CI (99.9%): [2.044, 4.468] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.595 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.005 ms/op
Iteration   1: 3.823 ±(99.9%) 0.009 ms/op
Iteration   2: 3.745 ±(99.9%) 0.009 ms/op
Iteration   3: 3.747 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.745, 3.772, 3.823), stdev = 0.044
  CI (99.9%): [2.965, 4.578] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 19.500 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 3.246 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 23.335 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  15.931 ms/op
                 createUser·p0.9999: 27.259 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298791
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25359 
    [ 2.500,  5.000) = 266704 
    [ 5.000,  7.500) = 5717 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     25.488 ms/op
     p(99.9990) =     27.592 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.557 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  14.829 ms/op
                 existUser·p0.9999: 19.374 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  10.676 ms/op
                 existUser·p0.9999: 20.146 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  8.470 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307643
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23675 
    [ 2.500,  5.000) = 278688 
    [ 5.000,  7.500) = 4636 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     20.619 ms/op
     p(99.9990) =     22.431 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 7.599 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.011 ms/op
Iteration   1: 3.182 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.249 ms/op
                 getUser·p0.999:  15.811 ms/op
                 getUser·p0.9999: 22.707 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.294 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 21.514 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298739
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9232 
    [ 2.500,  5.000) = 280766 
    [ 5.000,  7.500) = 7799 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     15.697 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.594 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 9.673 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.013 ms/op
Iteration   1: 3.775 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.639 ms/op
                 listUser·p0.9999: 20.646 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 3.881 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 19.733 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 3.743 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 13.861 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252708
  mean =      3.799 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 242968 
    [ 5.000,  7.500) = 7884 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.767 ms/op
     p(99.9900) =     19.914 ms/op
     p(99.9990) =     21.811 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.552 ± 0.345  ops/ms
ClientPb.existUser                       thrpt       3  10.447 ± 3.622  ops/ms
ClientPb.getUser                         thrpt       3   9.878 ± 2.810  ops/ms
ClientPb.listUser                        thrpt       3   8.329 ± 3.113  ops/ms
ClientPb.createUser                       avgt       3   3.201 ± 2.062   ms/op
ClientPb.existUser                        avgt       3   3.011 ± 0.595   ms/op
ClientPb.getUser                          avgt       3   3.256 ± 1.212   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 0.807   ms/op
ClientPb.createUser                     sample  298791   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.488           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.787           ms/op
ClientPb.existUser                      sample  307643   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.619           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  298739   3.211 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.697           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  252708   3.799 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.767           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.413           ms/op
