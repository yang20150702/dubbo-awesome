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
# Warmup Iteration   1: 1.533 ops/ms
# Warmup Iteration   2: 3.712 ops/ms
# Warmup Iteration   3: 7.238 ops/ms
Iteration   1: 7.299 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.804 ±(99.9%) 8.040 ops/ms [Average]
  (min, avg, max) = (7.299, 7.804, 8.108), stdev = 0.441
  CI (99.9%): [≈ 0, 15.845] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.225 ops/ms
# Warmup Iteration   2: 7.156 ops/ms
# Warmup Iteration   3: 8.197 ops/ms
Iteration   1: 8.540 ops/ms
Iteration   2: 8.393 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.385 ±(99.9%) 2.900 ops/ms [Average]
  (min, avg, max) = (8.223, 8.385, 8.540), stdev = 0.159
  CI (99.9%): [5.485, 11.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 6.307 ops/ms
# Warmup Iteration   3: 7.316 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.257 ±(99.9%) 2.641 ops/ms [Average]
  (min, avg, max) = (8.094, 8.257, 8.370), stdev = 0.145
  CI (99.9%): [5.616, 10.898] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.398 ops/ms
# Warmup Iteration   3: 6.643 ops/ms
Iteration   1: 6.898 ops/ms
Iteration   2: 6.851 ops/ms
Iteration   3: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.957 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (6.851, 6.957, 7.123), stdev = 0.145
  CI (99.9%): [4.304, 9.611] (assumes normal distribution)


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
# Warmup Iteration   1: 12.338 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
Iteration   2: 3.900 ±(99.9%) 0.012 ms/op
Iteration   3: 4.064 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.967 ±(99.9%) 1.580 ms/op [Average]
  (min, avg, max) = (3.900, 3.967, 4.064), stdev = 0.087
  CI (99.9%): [2.387, 5.546] (assumes normal distribution)


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
# Warmup Iteration   1: 12.747 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.005 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
Iteration   2: 3.773 ±(99.9%) 0.005 ms/op
Iteration   3: 3.821 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.800 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.773, 3.800, 3.821), stdev = 0.025
  CI (99.9%): [3.352, 4.247] (assumes normal distribution)


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
# Warmup Iteration   1: 13.736 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.005 ms/op
Iteration   1: 3.987 ±(99.9%) 0.008 ms/op
Iteration   2: 3.870 ±(99.9%) 0.008 ms/op
Iteration   3: 3.854 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.904 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.854, 3.904, 3.987), stdev = 0.073
  CI (99.9%): [2.574, 5.233] (assumes normal distribution)


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
# Warmup Iteration   1: 15.718 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.338 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.547 ±(99.9%) 0.012 ms/op
Iteration   1: 4.547 ±(99.9%) 0.012 ms/op
Iteration   2: 4.592 ±(99.9%) 0.014 ms/op
Iteration   3: 4.683 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.607 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (4.547, 4.607, 4.683), stdev = 0.070
  CI (99.9%): [3.339, 5.875] (assumes normal distribution)


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
# Warmup Iteration   1: 13.338 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.020 ms/op
Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 30.808 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   2: 4.030 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  24.837 ms/op
                 createUser·p0.9999: 32.934 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241360
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 159 
    [ 2.500,  5.000) = 228699 
    [ 5.000,  7.500) = 10392 
    [ 7.500, 10.000) = 1653 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.220 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     34.025 ms/op
     p(99.9990) =     35.532 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 11.017 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
Iteration   1: 3.862 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.835 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  24.248 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  13.328 ms/op
                 existUser·p0.9999: 32.245 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  15.991 ms/op
                 existUser·p0.9999: 34.309 ms/op
                 existUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252118
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 245374 
    [ 5.000,  7.500) = 4835 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     34.535 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 12.511 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.016 ms/op
Iteration   1: 4.104 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.991 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  23.859 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 3.850 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.942 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.252 ms/op
                 getUser·p0.9999: 27.439 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.984 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  27.447 ms/op
                 getUser·p0.9999: 30.637 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241475
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 228673 
    [ 5.000,  7.500) = 9753 
    [ 7.500, 10.000) = 2231 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     23.743 ms/op
     p(99.9900) =     29.341 ms/op
     p(99.9990) =     31.491 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 13.272 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.243 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.016 ms/op
Iteration   1: 4.693 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   8.606 ms/op
                 listUser·p0.999:  23.263 ms/op
                 listUser·p0.9999: 26.135 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.540 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 18.808 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.623 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.313 ms/op
                 listUser·p0.999:  17.429 ms/op
                 listUser·p0.9999: 19.115 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207581
  mean =      4.618 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 182777 
    [ 5.000,  7.500) = 21525 
    [ 7.500, 10.000) = 2332 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.177 ms/op
     p(99.9000) =     18.298 ms/op
     p(99.9900) =     25.370 ms/op
     p(99.9990) =     26.691 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.804 ± 8.040  ops/ms
ClientPb.existUser                       thrpt       3   8.385 ± 2.900  ops/ms
ClientPb.getUser                         thrpt       3   8.257 ± 2.641  ops/ms
ClientPb.listUser                        thrpt       3   6.957 ± 2.654  ops/ms
ClientPb.createUser                       avgt       3   3.967 ± 1.580   ms/op
ClientPb.existUser                        avgt       3   3.800 ± 0.448   ms/op
ClientPb.getUser                          avgt       3   3.904 ± 1.330   ms/op
ClientPb.listUser                         avgt       3   4.607 ± 1.268   ms/op
ClientPb.createUser                     sample  241360   3.975 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.011           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.220           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.890           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.717           ms/op
ClientPb.existUser                      sample  252118   3.804 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.660           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  241475   3.976 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.719           ms/op
ClientPb.listUser                       sample  207581   4.618 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.542           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.177           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.298           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.001           ms/op
