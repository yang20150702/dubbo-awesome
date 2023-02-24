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
# Warmup Iteration   1: 1.600 ops/ms
# Warmup Iteration   2: 3.493 ops/ms
# Warmup Iteration   3: 7.069 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.952 ±(99.9%) 3.527 ops/ms [Average]
  (min, avg, max) = (7.732, 7.952, 8.091), stdev = 0.193
  CI (99.9%): [4.425, 11.480] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.207 ops/ms
# Warmup Iteration   2: 6.445 ops/ms
# Warmup Iteration   3: 7.601 ops/ms
Iteration   1: 7.439 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.099 ±(99.9%) 10.553 ops/ms [Average]
  (min, avg, max) = (7.439, 8.099, 8.516), stdev = 0.578
  CI (99.9%): [≈ 0, 18.653] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 6.765 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 8.378 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.272 ±(99.9%) 2.117 ops/ms [Average]
  (min, avg, max) = (8.148, 8.272, 8.378), stdev = 0.116
  CI (99.9%): [6.155, 10.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.845 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 6.750 ops/ms
Iteration   2: 6.852 ops/ms
Iteration   3: 6.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.774 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (6.719, 6.774, 6.852), stdev = 0.070
  CI (99.9%): [5.501, 8.047] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.914 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.479 ±(99.9%) 0.006 ms/op
Iteration   1: 3.939 ±(99.9%) 0.008 ms/op
Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
Iteration   3: 3.919 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.945 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.919, 3.945, 3.976), stdev = 0.029
  CI (99.9%): [3.416, 4.474] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.155 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.006 ms/op
Iteration   1: 3.920 ±(99.9%) 0.005 ms/op
Iteration   2: 3.923 ±(99.9%) 0.005 ms/op
Iteration   3: 3.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.894 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.840, 3.894, 3.923), stdev = 0.047
  CI (99.9%): [3.034, 4.755] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.378 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.007 ms/op
Iteration   1: 4.012 ±(99.9%) 0.008 ms/op
Iteration   2: 3.838 ±(99.9%) 0.009 ms/op
Iteration   3: 4.009 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.953 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (3.838, 3.953, 4.012), stdev = 0.100
  CI (99.9%): [2.133, 5.773] (assumes normal distribution)


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
# Warmup Iteration   1: 14.040 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.902 ±(99.9%) 0.008 ms/op
Iteration   1: 4.844 ±(99.9%) 0.012 ms/op
Iteration   2: 4.682 ±(99.9%) 0.010 ms/op
Iteration   3: 4.531 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.686 ±(99.9%) 2.857 ms/op [Average]
  (min, avg, max) = (4.531, 4.686, 4.844), stdev = 0.157
  CI (99.9%): [1.829, 7.543] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.720 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.506 ±(99.9%) 0.021 ms/op
Iteration   1: 4.044 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  23.325 ms/op
                 createUser·p0.9999: 28.606 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 3.877 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.991 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  11.608 ms/op
                 createUser·p0.9999: 28.361 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.804 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  37.607 ms/op
                 createUser·p0.9999: 46.727 ms/op
                 createUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245746
  mean =      3.906 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 234299 
    [ 5.000, 10.000) = 10790 
    [10.000, 15.000) = 380 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 50 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     22.668 ms/op
     p(99.9900) =     46.100 ms/op
     p(99.9990) =     48.401 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.351 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.447 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 24.041 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 4.027 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 30.083 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 3.867 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   7.353 ms/op
                 existUser·p0.999:  10.628 ms/op
                 existUser·p0.9999: 27.516 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245447
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 232414 
    [ 5.000,  7.500) = 10246 
    [ 7.500, 10.000) = 1870 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     12.626 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     31.350 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 13.278 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.014 ms/op
Iteration   1: 4.053 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  23.402 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 34.398 ms/op
                 getUser·p1.00:   34.865 ms/op

Iteration   3: 3.944 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  28.109 ms/op
                 getUser·p0.9999: 31.024 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240536
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 225900 
    [ 5.000,  7.500) = 11687 
    [ 7.500, 10.000) = 2239 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     23.311 ms/op
     p(99.9900) =     33.616 ms/op
     p(99.9990) =     34.839 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 13.771 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.281 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.021 ms/op
Iteration   1: 4.805 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.050 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   9.210 ms/op
                 listUser·p0.999:  26.012 ms/op
                 listUser·p0.9999: 28.324 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 4.518 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 24.573 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 4.936 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  17.674 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202124
  mean =      4.747 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 167041 
    [ 5.000,  7.500) = 29241 
    [ 7.500, 10.000) = 4401 
    [10.000, 12.500) = 830 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.050 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     20.869 ms/op
     p(99.9900) =     28.099 ms/op
     p(99.9990) =     30.210 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.952 ±  3.527  ops/ms
ClientPb.existUser                       thrpt       3   8.099 ± 10.553  ops/ms
ClientPb.getUser                         thrpt       3   8.272 ±  2.117  ops/ms
ClientPb.listUser                        thrpt       3   6.774 ±  1.273  ops/ms
ClientPb.createUser                       avgt       3   3.945 ±  0.529   ms/op
ClientPb.existUser                        avgt       3   3.894 ±  0.861   ms/op
ClientPb.getUser                          avgt       3   3.953 ±  1.820   ms/op
ClientPb.listUser                         avgt       3   4.686 ±  2.857   ms/op
ClientPb.createUser                     sample  245746   3.906 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.417            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.489            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.956            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.004            ms/op
ClientPb.createUser:createUser·p0.999   sample          22.668            ms/op
ClientPb.createUser:createUser·p0.9999  sample          46.100            ms/op
ClientPb.createUser:createUser·p1.00    sample          48.628            ms/op
ClientPb.existUser                      sample  245447   3.908 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.366            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.777            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.038            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.455            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.626            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.541            ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425            ms/op
ClientPb.getUser                        sample  240536   3.991 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.530            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.251            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.733            ms/op
ClientPb.getUser:getUser·p0.999         sample          23.311            ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.616            ms/op
ClientPb.getUser:getUser·p1.00          sample          34.865            ms/op
ClientPb.listUser                       sample  202124   4.747 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.050            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.160            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.869            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.099            ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278            ms/op
