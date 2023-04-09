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
# Warmup Iteration   1: 1.774 ops/ms
# Warmup Iteration   2: 3.770 ops/ms
# Warmup Iteration   3: 7.472 ops/ms
Iteration   1: 7.406 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.748 ±(99.9%) 5.832 ops/ms [Average]
  (min, avg, max) = (7.406, 7.748, 8.039), stdev = 0.320
  CI (99.9%): [1.916, 13.580] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.469 ops/ms
# Warmup Iteration   2: 6.475 ops/ms
# Warmup Iteration   3: 8.375 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.481 ±(99.9%) 4.572 ops/ms [Average]
  (min, avg, max) = (8.204, 8.481, 8.691), stdev = 0.251
  CI (99.9%): [3.909, 13.053] (assumes normal distribution)


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
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 7.010 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.088 ±(99.9%) 5.544 ops/ms [Average]
  (min, avg, max) = (7.780, 8.088, 8.387), stdev = 0.304
  CI (99.9%): [2.544, 13.632] (assumes normal distribution)


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
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 6.130 ops/ms
# Warmup Iteration   3: 7.174 ops/ms
Iteration   1: 7.178 ops/ms
Iteration   2: 6.972 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.100 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (6.972, 7.100, 7.178), stdev = 0.111
  CI (99.9%): [5.066, 9.133] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.733 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.004 ms/op
Iteration   1: 3.952 ±(99.9%) 0.008 ms/op
Iteration   2: 4.055 ±(99.9%) 0.006 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.007 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.952, 4.007, 4.055), stdev = 0.052
  CI (99.9%): [3.055, 4.959] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.527 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.008 ms/op
Iteration   1: 3.696 ±(99.9%) 0.007 ms/op
Iteration   2: 3.878 ±(99.9%) 0.005 ms/op
Iteration   3: 3.733 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.769 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (3.696, 3.769, 3.878), stdev = 0.096
  CI (99.9%): [2.019, 5.519] (assumes normal distribution)


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
# Warmup Iteration   1: 12.525 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.970 ±(99.9%) 0.008 ms/op
Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
Iteration   3: 3.873 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.884 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (3.810, 3.884, 3.970), stdev = 0.081
  CI (99.9%): [2.411, 5.357] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.346 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.012 ms/op
Iteration   1: 4.735 ±(99.9%) 0.010 ms/op
Iteration   2: 4.425 ±(99.9%) 0.016 ms/op
Iteration   3: 4.469 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.543 ±(99.9%) 3.055 ms/op [Average]
  (min, avg, max) = (4.425, 4.543, 4.735), stdev = 0.167
  CI (99.9%): [1.488, 7.598] (assumes normal distribution)


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
# Warmup Iteration   1: 14.060 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.637 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.018 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.997 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.170 ms/op
                 createUser·p0.999:  26.088 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 3.839 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  12.116 ms/op
                 createUser·p0.9999: 33.969 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243598
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 229038 
    [ 5.000,  7.500) = 12947 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     24.242 ms/op
     p(99.9900) =     32.503 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 11.376 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
Iteration   1: 3.644 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.841 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  21.955 ms/op
                 existUser·p0.9999: 27.157 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  10.853 ms/op
                 existUser·p0.9999: 26.800 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 3.702 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  25.559 ms/op
                 existUser·p0.9999: 28.410 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 259764
  mean =      3.695 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 732 
    [ 2.500,  5.000) = 252645 
    [ 5.000,  7.500) = 5033 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     28.751 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 12.950 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.013 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 23.290 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.865 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  11.505 ms/op
                 getUser·p0.9999: 25.288 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.944 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 26.082 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246959
  mean =      3.886 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 234783 
    [ 5.000,  7.500) = 10330 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     25.733 ms/op
     p(99.9990) =     26.537 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 13.256 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.607 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.028 ms/op
Iteration   1: 4.879 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  26.138 ms/op
                 listUser·p0.9999: 28.209 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.565 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  18.513 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   3: 4.498 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  17.854 ms/op
                 listUser·p0.9999: 20.116 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206806
  mean =      4.642 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 169780 
    [ 5.000,  7.500) = 31501 
    [ 7.500, 10.000) = 4301 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 107 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     28.914 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.748 ± 5.832  ops/ms
ClientPb.existUser                       thrpt       3   8.481 ± 4.572  ops/ms
ClientPb.getUser                         thrpt       3   8.088 ± 5.544  ops/ms
ClientPb.listUser                        thrpt       3   7.100 ± 2.034  ops/ms
ClientPb.createUser                       avgt       3   4.007 ± 0.952   ms/op
ClientPb.existUser                        avgt       3   3.769 ± 1.750   ms/op
ClientPb.getUser                          avgt       3   3.884 ± 1.473   ms/op
ClientPb.listUser                         avgt       3   4.543 ± 3.055   ms/op
ClientPb.createUser                     sample  243598   3.939 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.503           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  259764   3.695 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.262           ms/op
ClientPb.getUser                        sample  246959   3.886 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.733           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  206806   4.642 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.825           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.689           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
