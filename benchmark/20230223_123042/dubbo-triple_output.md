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
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 5.944 ops/ms
# Warmup Iteration   3: 8.410 ops/ms
Iteration   1: 10.026 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.066 ±(99.9%) 6.278 ops/ms [Average]
  (min, avg, max) = (9.744, 10.066, 10.429), stdev = 0.344
  CI (99.9%): [3.788, 16.344] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ops/ms
# Warmup Iteration   2: 9.673 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.061 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.385 ±(99.9%) 5.474 ops/ms [Average]
  (min, avg, max) = (10.061, 10.385, 10.653), stdev = 0.300
  CI (99.9%): [4.911, 15.860] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ops/ms
# Warmup Iteration   2: 9.163 ops/ms
# Warmup Iteration   3: 9.550 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.432 ops/ms
Iteration   3: 9.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.092 ±(99.9%) 5.485 ops/ms [Average]
  (min, avg, max) = (9.863, 10.092, 10.432), stdev = 0.301
  CI (99.9%): [4.607, 15.577] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.447 ops/ms
# Warmup Iteration   2: 7.802 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 8.478 ops/ms
Iteration   2: 8.580 ops/ms
Iteration   3: 8.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.612 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (8.478, 8.612, 8.779), stdev = 0.153
  CI (99.9%): [5.822, 11.402] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.730 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.008 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
Iteration   2: 3.142 ±(99.9%) 0.004 ms/op
Iteration   3: 3.148 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.142, 3.164, 3.202), stdev = 0.033
  CI (99.9%): [2.561, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 7.794 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.005 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
Iteration   3: 3.061 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.091 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.061, 3.091, 3.143), stdev = 0.045
  CI (99.9%): [2.276, 3.906] (assumes normal distribution)


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
# Warmup Iteration   1: 7.494 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.004 ms/op
Iteration   1: 3.069 ±(99.9%) 0.004 ms/op
Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
Iteration   3: 3.188 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.147 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (3.069, 3.147, 3.188), stdev = 0.068
  CI (99.9%): [1.915, 4.379] (assumes normal distribution)


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
# Warmup Iteration   1: 8.542 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.003 ms/op
Iteration   1: 3.731 ±(99.9%) 0.007 ms/op
Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
Iteration   3: 3.741 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.740 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.731, 3.740, 3.748), stdev = 0.009
  CI (99.9%): [3.580, 3.900] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.471 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  18.492 ms/op
                 createUser·p0.9999: 23.586 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  8.429 ms/op
                 createUser·p0.9999: 23.510 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298734
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13106 
    [ 2.500,  5.000) = 280628 
    [ 5.000,  7.500) = 4235 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     16.732 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     25.204 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 6.416 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 19.921 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  14.571 ms/op
                 existUser·p0.9999: 21.285 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.560 ms/op
                 existUser·p0.9999: 20.783 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307785
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16521 
    [ 2.500,  5.000) = 287385 
    [ 5.000,  7.500) = 3144 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.277 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 7.585 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
Iteration   1: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  18.122 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.736 ms/op
                 getUser·p0.9999: 22.026 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  15.843 ms/op
                 getUser·p0.9999: 23.698 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296662
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21106 
    [ 2.500,  5.000) = 268054 
    [ 5.000,  7.500) = 6839 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     22.304 ms/op
     p(99.9990) =     24.562 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 8.465 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.012 ms/op
Iteration   1: 3.811 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.284 ms/op
                 listUser·p0.9999: 21.279 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 3.686 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.748 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 14.844 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.652 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.055 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258237
  mean =      3.715 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 251232 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 350 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.054 ms/op
     p(99.9900) =     19.985 ms/op
     p(99.9990) =     24.879 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.066 ± 6.278  ops/ms
ClientPb.existUser                       thrpt       3  10.385 ± 5.474  ops/ms
ClientPb.getUser                         thrpt       3  10.092 ± 5.485  ops/ms
ClientPb.listUser                        thrpt       3   8.612 ± 2.790  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 0.603   ms/op
ClientPb.existUser                        avgt       3   3.091 ± 0.815   ms/op
ClientPb.getUser                          avgt       3   3.147 ± 1.232   ms/op
ClientPb.listUser                         avgt       3   3.740 ± 0.160   ms/op
ClientPb.createUser                     sample  298734   3.210 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.732           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.101           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.985           ms/op
ClientPb.existUser                      sample  307785   3.116 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.243           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.790           ms/op
ClientPb.getUser                        sample  296662   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.297           ms/op
ClientPb.listUser                       sample  258237   3.715 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.054           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.985           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.969           ms/op
