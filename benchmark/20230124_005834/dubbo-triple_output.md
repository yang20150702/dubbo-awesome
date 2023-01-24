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
# Warmup Iteration   1: 1.973 ops/ms
# Warmup Iteration   2: 4.401 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 8.709 ops/ms
Iteration   2: 8.874 ops/ms
Iteration   3: 8.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.781 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (8.709, 8.781, 8.874), stdev = 0.084
  CI (99.9%): [7.244, 10.319] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.725 ops/ms
# Warmup Iteration   2: 8.325 ops/ms
# Warmup Iteration   3: 9.036 ops/ms
Iteration   1: 9.467 ops/ms
Iteration   2: 9.619 ops/ms
Iteration   3: 9.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.611 ±(99.9%) 2.553 ops/ms [Average]
  (min, avg, max) = (9.467, 9.611, 9.746), stdev = 0.140
  CI (99.9%): [7.057, 12.164] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 8.486 ops/ms
# Warmup Iteration   3: 8.514 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.242 ops/ms
Iteration   3: 9.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.211 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (9.176, 9.211, 9.242), stdev = 0.033
  CI (99.9%): [8.607, 9.815] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 6.930 ops/ms
# Warmup Iteration   3: 7.426 ops/ms
Iteration   1: 7.581 ops/ms
Iteration   2: 7.876 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.728 ±(99.9%) 2.691 ops/ms [Average]
  (min, avg, max) = (7.581, 7.728, 7.876), stdev = 0.147
  CI (99.9%): [5.037, 10.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.407 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.006 ms/op
Iteration   1: 3.532 ±(99.9%) 0.008 ms/op
Iteration   2: 3.617 ±(99.9%) 0.006 ms/op
Iteration   3: 3.662 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.604 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (3.532, 3.604, 3.662), stdev = 0.066
  CI (99.9%): [2.401, 4.807] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.586 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.007 ms/op
Iteration   1: 3.530 ±(99.9%) 0.008 ms/op
Iteration   2: 3.613 ±(99.9%) 0.007 ms/op
Iteration   3: 3.390 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.511 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (3.390, 3.511, 3.613), stdev = 0.112
  CI (99.9%): [1.462, 5.559] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.424 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.006 ms/op
Iteration   1: 3.463 ±(99.9%) 0.004 ms/op
Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
Iteration   3: 3.554 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.509 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (3.463, 3.509, 3.554), stdev = 0.045
  CI (99.9%): [2.682, 4.337] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.555 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.962 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.009 ms/op
Iteration   1: 4.227 ±(99.9%) 0.007 ms/op
Iteration   2: 4.091 ±(99.9%) 0.012 ms/op
Iteration   3: 4.195 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.171 ±(99.9%) 1.297 ms/op [Average]
  (min, avg, max) = (4.091, 4.171, 4.227), stdev = 0.071
  CI (99.9%): [2.874, 5.468] (assumes normal distribution)


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
# Warmup Iteration   1: 9.866 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.012 ms/op
Iteration   1: 3.596 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   2: 3.550 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  27.357 ms/op
                 createUser·p0.9999: 30.343 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.590 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  32.078 ms/op
                 createUser·p0.9999: 38.410 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268103
  mean =      3.579 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2534 
    [ 2.500,  5.000) = 256939 
    [ 5.000,  7.500) = 7203 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 90 
    [32.500, 35.000) = 59 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     25.982 ms/op
     p(99.9900) =     34.104 ms/op
     p(99.9990) =     38.797 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 10.299 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
Iteration   1: 3.509 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 27.350 ms/op
                 existUser·p1.00:   30.769 ms/op

Iteration   2: 3.392 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  27.042 ms/op
                 existUser·p0.9999: 28.967 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 3.350 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  27.814 ms/op
                 existUser·p0.9999: 32.864 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280900
  mean =      3.415 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9253 
    [ 2.500,  5.000) = 264236 
    [ 5.000,  7.500) = 5680 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 118 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     16.730 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 10.870 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.012 ms/op
Iteration   1: 3.507 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  22.562 ms/op
                 getUser·p0.9999: 26.931 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.524 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 31.250 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 3.645 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.891 ms/op
                 getUser·p0.999:  25.081 ms/op
                 getUser·p0.9999: 34.553 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269652
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 917 
    [ 2.500,  5.000) = 261634 
    [ 5.000,  7.500) = 5667 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.443 ms/op
     p(99.9000) =     23.408 ms/op
     p(99.9900) =     33.523 ms/op
     p(99.9990) =     35.973 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 11.140 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.018 ms/op
Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  24.415 ms/op
                 listUser·p0.9999: 29.645 ms/op
                 listUser·p1.00:   30.343 ms/op

Iteration   2: 4.140 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.753 ms/op
                 listUser·p0.999:  17.060 ms/op
                 listUser·p0.9999: 18.916 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.217 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 20.478 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229619
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 219975 
    [ 5.000,  7.500) = 6810 
    [ 7.500, 10.000) = 1767 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     28.446 ms/op
     p(99.9990) =     30.314 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.781 ± 1.537  ops/ms
ClientPb.existUser                       thrpt       3   9.611 ± 2.553  ops/ms
ClientPb.getUser                         thrpt       3   9.211 ± 0.604  ops/ms
ClientPb.listUser                        thrpt       3   7.728 ± 2.691  ops/ms
ClientPb.createUser                       avgt       3   3.604 ± 1.203   ms/op
ClientPb.existUser                        avgt       3   3.511 ± 2.049   ms/op
ClientPb.getUser                          avgt       3   3.509 ± 0.827   ms/op
ClientPb.listUser                         avgt       3   4.171 ± 1.297   ms/op
ClientPb.createUser                     sample  268103   3.579 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.104           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  280900   3.415 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.649           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  269652   3.558 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.565           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.443           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.408           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  229619   4.179 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.446           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.343           ms/op
