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
# Warmup Iteration   1: 1.043 ops/ms
# Warmup Iteration   2: 2.595 ops/ms
# Warmup Iteration   3: 5.252 ops/ms
Iteration   1: 5.316 ops/ms
Iteration   2: 5.391 ops/ms
Iteration   3: 5.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.453 ±(99.9%) 3.221 ops/ms [Average]
  (min, avg, max) = (5.316, 5.453, 5.652), stdev = 0.177
  CI (99.9%): [2.232, 8.674] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.628 ops/ms
# Warmup Iteration   2: 4.831 ops/ms
# Warmup Iteration   3: 6.060 ops/ms
Iteration   1: 5.946 ops/ms
Iteration   2: 5.921 ops/ms
Iteration   3: 6.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.961 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (5.921, 5.961, 6.016), stdev = 0.049
  CI (99.9%): [5.065, 6.857] (assumes normal distribution)


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
# Warmup Iteration   1: 1.626 ops/ms
# Warmup Iteration   2: 4.623 ops/ms
# Warmup Iteration   3: 5.894 ops/ms
Iteration   1: 5.669 ops/ms
Iteration   2: 5.496 ops/ms
Iteration   3: 5.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.572 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (5.496, 5.572, 5.669), stdev = 0.089
  CI (99.9%): [3.957, 7.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.322 ops/ms
# Warmup Iteration   2: 3.928 ops/ms
# Warmup Iteration   3: 4.767 ops/ms
Iteration   1: 4.923 ops/ms
Iteration   2: 4.888 ops/ms
Iteration   3: 5.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.962 ±(99.9%) 1.816 ops/ms [Average]
  (min, avg, max) = (4.888, 4.962, 5.075), stdev = 0.100
  CI (99.9%): [3.146, 6.777] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.318 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.467 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.141 ±(99.9%) 0.017 ms/op
Iteration   1: 5.989 ±(99.9%) 0.012 ms/op
Iteration   2: 5.642 ±(99.9%) 0.016 ms/op
Iteration   3: 5.578 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.736 ±(99.9%) 4.036 ms/op [Average]
  (min, avg, max) = (5.578, 5.736, 5.989), stdev = 0.221
  CI (99.9%): [1.700, 9.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.033 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.645 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.464 ±(99.9%) 0.014 ms/op
Iteration   1: 5.675 ±(99.9%) 0.010 ms/op
Iteration   2: 5.594 ±(99.9%) 0.008 ms/op
Iteration   3: 5.248 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.506 ±(99.9%) 4.135 ms/op [Average]
  (min, avg, max) = (5.248, 5.506, 5.675), stdev = 0.227
  CI (99.9%): [1.370, 9.641] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.596 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.354 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.701 ±(99.9%) 0.011 ms/op
Iteration   1: 5.812 ±(99.9%) 0.008 ms/op
Iteration   2: 5.742 ±(99.9%) 0.008 ms/op
Iteration   3: 5.473 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.675 ±(99.9%) 3.267 ms/op [Average]
  (min, avg, max) = (5.473, 5.675, 5.812), stdev = 0.179
  CI (99.9%): [2.409, 8.942] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.710 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.335 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.578 ±(99.9%) 0.014 ms/op
Iteration   1: 6.554 ±(99.9%) 0.015 ms/op
Iteration   2: 6.693 ±(99.9%) 0.012 ms/op
Iteration   3: 6.443 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.564 ±(99.9%) 2.286 ms/op [Average]
  (min, avg, max) = (6.443, 6.564, 6.693), stdev = 0.125
  CI (99.9%): [4.278, 8.850] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.616 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.054 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.389 ±(99.9%) 0.029 ms/op
Iteration   1: 5.848 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.318 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.553 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   11.485 ms/op
                 createUser·p0.999:  21.998 ms/op
                 createUser·p0.9999: 26.658 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 5.621 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.580 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 30.714 ms/op
                 createUser·p1.00:   31.654 ms/op

Iteration   3: 5.799 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.748 ms/op
                 createUser·p0.999:  26.306 ms/op
                 createUser·p0.9999: 30.326 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166646
  mean =      5.754 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 45566 
    [ 5.000,  7.500) = 107613 
    [ 7.500, 10.000) = 10450 
    [10.000, 12.500) = 2010 
    [12.500, 15.000) = 580 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.168 ms/op
     p(95.0000) =      8.331 ms/op
     p(99.0000) =     11.363 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     30.289 ms/op
     p(99.9990) =     31.610 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.330 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.501 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.794 ±(99.9%) 0.023 ms/op
Iteration   1: 5.595 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.209 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   11.436 ms/op
                 existUser·p0.999:  15.598 ms/op
                 existUser·p0.9999: 32.955 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   2: 5.441 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.922 ms/op
                 existUser·p0.99:   12.567 ms/op
                 existUser·p0.999:  26.477 ms/op
                 existUser·p0.9999: 60.760 ms/op
                 existUser·p1.00:   63.832 ms/op

Iteration   3: 5.413 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   10.895 ms/op
                 existUser·p0.999:  25.716 ms/op
                 existUser·p0.9999: 31.982 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174996
  mean =      5.482 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 73662 
    [ 5.000, 10.000) = 98106 
    [10.000, 15.000) = 2806 
    [15.000, 20.000) = 262 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 22 
    [60.000, 65.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     59.408 ms/op
     p(99.9990) =     61.571 ms/op
     p(99.9999) =     63.832 ms/op
    p(100.0000) =     63.832 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.404 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.818 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.883 ±(99.9%) 0.023 ms/op
Iteration   1: 5.942 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   9.421 ms/op
                 getUser·p0.99:   13.615 ms/op
                 getUser·p0.999:  25.433 ms/op
                 getUser·p0.9999: 29.360 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   2: 5.993 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.758 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   12.976 ms/op
                 getUser·p0.999:  26.356 ms/op
                 getUser·p0.9999: 31.414 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   3: 5.748 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.642 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.118 ms/op
                 getUser·p0.99:   10.912 ms/op
                 getUser·p0.999:  14.604 ms/op
                 getUser·p0.9999: 32.113 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162796
  mean =      5.892 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 36854 
    [ 5.000,  7.500) = 110744 
    [ 7.500, 10.000) = 10054 
    [10.000, 12.500) = 3375 
    [12.500, 15.000) = 1075 
    [15.000, 17.500) = 297 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     12.698 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     33.102 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.195 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 8.043 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.997 ±(99.9%) 0.031 ms/op
Iteration   1: 6.885 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   14.156 ms/op
                 listUser·p0.999:  29.704 ms/op
                 listUser·p0.9999: 35.848 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   2: 6.699 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.588 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   13.664 ms/op
                 listUser·p0.999:  30.286 ms/op
                 listUser·p0.9999: 34.945 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.594 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.207 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.738 ms/op
                 listUser·p0.999:  29.065 ms/op
                 listUser·p0.9999: 34.032 ms/op
                 listUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142792
  mean =      6.724 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2582 
    [ 5.000,  7.500) = 118277 
    [ 7.500, 10.000) = 16698 
    [10.000, 12.500) = 3307 
    [12.500, 15.000) = 1072 
    [15.000, 17.500) = 392 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      6.341 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.273 ms/op
     p(99.0000) =     13.468 ms/op
     p(99.9000) =     29.793 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     38.086 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.453 ± 3.221  ops/ms
ClientPb.existUser                       thrpt       3   5.961 ± 0.896  ops/ms
ClientPb.getUser                         thrpt       3   5.572 ± 1.616  ops/ms
ClientPb.listUser                        thrpt       3   4.962 ± 1.816  ops/ms
ClientPb.createUser                       avgt       3   5.736 ± 4.036   ms/op
ClientPb.existUser                        avgt       3   5.506 ± 4.135   ms/op
ClientPb.getUser                          avgt       3   5.675 ± 3.267   ms/op
ClientPb.listUser                         avgt       3   6.564 ± 2.286   ms/op
ClientPb.createUser                     sample  166646   5.754 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.318           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.331           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.363           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.807           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.289           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.654           ms/op
ClientPb.existUser                      sample  174996   5.482 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.086           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.022           ms/op
ClientPb.existUser:existUser·p0.9999    sample          59.408           ms/op
ClientPb.existUser:existUser·p1.00      sample          63.832           ms/op
ClientPb.getUser                        sample  162796   5.892 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.704           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.698           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  142792   6.724 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.277           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.341           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.793           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
