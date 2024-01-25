# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ops/ms
# Warmup Iteration   2: 12.174 ops/ms
# Warmup Iteration   3: 12.266 ops/ms
Iteration   1: 12.344 ops/ms
Iteration   2: 12.503 ops/ms
Iteration   3: 12.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.487 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (12.344, 12.487, 12.613), stdev = 0.135
  CI (99.9%): [10.024, 14.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ops/ms
# Warmup Iteration   2: 13.041 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 13.243 ops/ms
Iteration   2: 13.347 ops/ms
Iteration   3: 13.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.290 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (13.243, 13.290, 13.347), stdev = 0.053
  CI (99.9%): [12.331, 14.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.025 ops/ms
# Warmup Iteration   2: 12.739 ops/ms
# Warmup Iteration   3: 12.863 ops/ms
Iteration   1: 13.003 ops/ms
Iteration   2: 12.928 ops/ms
Iteration   3: 12.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.935 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (12.873, 12.935, 13.003), stdev = 0.065
  CI (99.9%): [11.742, 14.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.654 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (10.624, 10.654, 10.682), stdev = 0.029
  CI (99.9%): [10.125, 11.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.003 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.513, 2.540, 2.556), stdev = 0.024
  CI (99.9%): [2.102, 2.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.422, 2.429, 2.439), stdev = 0.009
  CI (99.9%): [2.264, 2.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.003 ms/op
Iteration   1: 2.493 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.493, 2.509, 2.519), stdev = 0.014
  CI (99.9%): [2.246, 2.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.729 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.020, 3.033, 3.040), stdev = 0.012
  CI (99.9%): [2.823, 3.243] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.032 ms/op
                 createUser·p0.9999: 17.572 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  9.141 ms/op
                 createUser·p0.9999: 11.964 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  9.875 ms/op
                 createUser·p0.9999: 12.274 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381340
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 184433 
    [ 2.500,  3.750) = 192016 
    [ 3.750,  5.000) = 3985 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      9.661 ms/op
     p(99.9900) =     15.254 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.711 ms/op
                 existUser·p0.9999: 14.404 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  7.354 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385844
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 191812 
    [ 2.500,  3.750) = 190184 
    [ 3.750,  5.000) = 2763 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 156 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.874 ms/op
     p(99.9900) =     13.947 ms/op
     p(99.9990) =     14.685 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  5.820 ms/op
                 getUser·p0.9999: 16.728 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 14.608 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.806 ms/op
                 getUser·p0.999:  9.229 ms/op
                 getUser·p0.9999: 11.721 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382507
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 189323 
    [ 2.500,  3.750) = 187896 
    [ 3.750,  5.000) = 4203 
    [ 5.000,  6.250) = 615 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     17.322 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.942 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.881 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.304 ms/op
                 listUser·p0.9999: 11.575 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.690 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315138
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 85134 
    [ 2.500,  3.750) = 188611 
    [ 3.750,  5.000) = 34018 
    [ 5.000,  6.250) = 5882 
    [ 6.250,  7.500) = 708 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     11.950 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.487 ± 2.463  ops/ms
ClientPb.existUser                       thrpt       3  13.290 ± 0.959  ops/ms
ClientPb.getUser                         thrpt       3  12.935 ± 1.193  ops/ms
ClientPb.listUser                        thrpt       3  10.654 ± 0.529  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.263   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.210   ms/op
ClientPb.createUser                     sample  381340   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.806           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.350           ms/op
ClientPb.existUser                      sample  385844   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.827           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.874           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.947           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  382507   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.760           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.832           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.252           ms/op
ClientPb.listUser                       sample  315138   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.899           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.042           ms/op
