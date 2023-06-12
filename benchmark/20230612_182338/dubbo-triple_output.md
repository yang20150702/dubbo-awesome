# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.942 ops/ms
# Warmup Iteration   2: 5.297 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 8.609 ops/ms
Iteration   2: 9.302 ops/ms
Iteration   3: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.106 ±(99.9%) 7.914 ops/ms [Average]
  (min, avg, max) = (8.609, 9.106, 9.407), stdev = 0.434
  CI (99.9%): [1.192, 17.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.617 ops/ms
# Warmup Iteration   3: 9.260 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 9.837 ops/ms
Iteration   3: 9.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.618 ±(99.9%) 4.774 ops/ms [Average]
  (min, avg, max) = (9.328, 9.618, 9.837), stdev = 0.262
  CI (99.9%): [4.844, 14.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 7.955 ops/ms
# Warmup Iteration   3: 8.941 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.151 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.288 ±(99.9%) 3.149 ops/ms [Average]
  (min, avg, max) = (9.151, 9.288, 9.482), stdev = 0.173
  CI (99.9%): [6.139, 12.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 7.019 ops/ms
# Warmup Iteration   3: 7.522 ops/ms
Iteration   1: 7.693 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.739 ±(99.9%) 0.830 ops/ms [Average]
  (min, avg, max) = (7.693, 7.739, 7.784), stdev = 0.045
  CI (99.9%): [6.909, 8.569] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.197 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
Iteration   2: 3.487 ±(99.9%) 0.010 ms/op
Iteration   3: 3.475 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (3.413, 3.459, 3.487), stdev = 0.040
  CI (99.9%): [2.735, 4.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.001 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.005 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
Iteration   2: 3.310 ±(99.9%) 0.013 ms/op
Iteration   3: 3.394 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.269, 3.324, 3.394), stdev = 0.064
  CI (99.9%): [2.157, 4.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.593 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.006 ms/op
Iteration   1: 3.391 ±(99.9%) 0.011 ms/op
Iteration   2: 3.530 ±(99.9%) 0.005 ms/op
Iteration   3: 3.594 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 1.899 ms/op [Average]
  (min, avg, max) = (3.391, 3.505, 3.594), stdev = 0.104
  CI (99.9%): [1.606, 5.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.089 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.006 ms/op
Iteration   1: 4.184 ±(99.9%) 0.008 ms/op
Iteration   2: 3.954 ±(99.9%) 0.017 ms/op
Iteration   3: 4.100 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.079 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.954, 4.079, 4.184), stdev = 0.117
  CI (99.9%): [1.950, 6.209] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.856 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.014 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  22.356 ms/op
                 createUser·p0.9999: 25.807 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.463 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 25.338 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.660 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  24.893 ms/op
                 createUser·p0.9999: 34.079 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274098
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8050 
    [ 2.500,  5.000) = 258141 
    [ 5.000,  7.500) = 6726 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     16.020 ms/op
     p(99.9900) =     32.460 ms/op
     p(99.9990) =     34.719 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.742 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
Iteration   1: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.799 ms/op
                 existUser·p0.999:  21.103 ms/op
                 existUser·p0.9999: 24.320 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.379 ms/op
                 existUser·p0.999:  21.728 ms/op
                 existUser·p0.9999: 31.114 ms/op
                 existUser·p1.00:   32.932 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  12.445 ms/op
                 existUser·p0.9999: 27.987 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280369
  mean =      3.422 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5340 
    [ 2.500,  5.000) = 269436 
    [ 5.000,  7.500) = 4763 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     12.511 ms/op
     p(99.9900) =     30.375 ms/op
     p(99.9990) =     31.562 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.331 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.012 ms/op
Iteration   1: 3.532 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  10.404 ms/op
                 getUser·p0.9999: 24.696 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.519 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.885 ms/op
                 getUser·p0.999:  22.939 ms/op
                 getUser·p0.9999: 27.122 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  24.022 ms/op
                 getUser·p0.9999: 29.538 ms/op
                 getUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272828
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10734 
    [ 2.500,  5.000) = 253666 
    [ 5.000,  7.500) = 7454 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.206 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.393 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.015 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.740 ms/op
                 listUser·p0.99:   7.793 ms/op
                 listUser·p0.999:  21.726 ms/op
                 listUser·p0.9999: 23.727 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  17.013 ms/op
                 listUser·p0.9999: 17.954 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.967 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 16.874 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240464
  mean =      3.990 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 233358 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 263 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.146 ms/op
     p(99.9000) =     16.196 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.299 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.106 ± 7.914  ops/ms
ClientPb.existUser                       thrpt       3   9.618 ± 4.774  ops/ms
ClientPb.getUser                         thrpt       3   9.288 ± 3.149  ops/ms
ClientPb.listUser                        thrpt       3   7.739 ± 0.830  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.724   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 1.167   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 1.899   ms/op
ClientPb.listUser                         avgt       3   4.079 ± 2.129   ms/op
ClientPb.createUser                     sample  274098   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.333           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  280369   3.422 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.375           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  272828   3.517 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.415           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.354           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  240464   3.990 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.618           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.146           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.196           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
