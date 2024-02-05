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
# Warmup Iteration   1: 4.918 ops/ms
# Warmup Iteration   2: 11.954 ops/ms
# Warmup Iteration   3: 12.305 ops/ms
Iteration   1: 12.481 ops/ms
Iteration   2: 12.479 ops/ms
Iteration   3: 12.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.498 ±(99.9%) 0.573 ops/ms [Average]
  (min, avg, max) = (12.479, 12.498, 12.534), stdev = 0.031
  CI (99.9%): [11.925, 13.071] (assumes normal distribution)


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
# Warmup Iteration   1: 7.965 ops/ms
# Warmup Iteration   2: 12.807 ops/ms
# Warmup Iteration   3: 12.901 ops/ms
Iteration   1: 12.849 ops/ms
Iteration   2: 12.920 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.868 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (12.835, 12.868, 12.920), stdev = 0.046
  CI (99.9%): [12.031, 13.705] (assumes normal distribution)


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
# Warmup Iteration   1: 7.390 ops/ms
# Warmup Iteration   2: 12.555 ops/ms
# Warmup Iteration   3: 12.723 ops/ms
Iteration   1: 12.656 ops/ms
Iteration   2: 12.719 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.707 ±(99.9%) 0.835 ops/ms [Average]
  (min, avg, max) = (12.656, 12.707, 12.745), stdev = 0.046
  CI (99.9%): [11.872, 13.542] (assumes normal distribution)


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
# Warmup Iteration   1: 6.603 ops/ms
# Warmup Iteration   2: 10.455 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.713 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (10.671, 10.713, 10.765), stdev = 0.048
  CI (99.9%): [9.844, 11.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (2.502, 2.524, 2.554), stdev = 0.027
  CI (99.9%): [2.027, 3.021] (assumes normal distribution)


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.002 ms/op
Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.480, 2.489, 2.495), stdev = 0.008
  CI (99.9%): [2.344, 2.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.530, 2.536, 2.541), stdev = 0.006
  CI (99.9%): [2.428, 2.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (3.022, 3.028, 3.035), stdev = 0.007
  CI (99.9%): [2.902, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  12.350 ms/op
                 createUser·p0.9999: 13.456 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.644 ms/op
                 createUser·p0.9999: 12.472 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 10.476 ms/op
                 createUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380341
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 181921 
    [ 2.500,  3.750) = 194217 
    [ 3.750,  5.000) = 3313 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      9.137 ms/op
     p(99.9900) =     13.204 ms/op
     p(99.9990) =     13.966 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 13.996 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  9.912 ms/op
                 existUser·p0.9999: 13.389 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  8.479 ms/op
                 existUser·p0.9999: 11.404 ms/op
                 existUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387171
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 188700 
    [ 2.500,  3.750) = 195192 
    [ 3.750,  5.000) = 2426 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.767 ms/op
     p(99.9990) =     14.403 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  11.457 ms/op
                 getUser·p0.9999: 13.513 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  10.078 ms/op
                 getUser·p0.9999: 12.396 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380142
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 187005 
    [ 2.500,  3.750) = 188343 
    [ 3.750,  5.000) = 3347 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 149 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     14.308 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 4.861 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.635 ms/op
                 listUser·p0.9999: 10.896 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.682 ms/op
                 listUser·p0.9999: 11.149 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.526 ms/op
                 listUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314959
  mean =      3.045 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 84063 
    [ 2.500,  3.750) = 190183 
    [ 3.750,  5.000) = 33562 
    [ 5.000,  6.250) = 5599 
    [ 6.250,  7.500) = 789 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     11.346 ms/op
     p(99.9990) =     11.925 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.498 ± 0.573  ops/ms
ClientPb.existUser                       thrpt       3  12.868 ± 0.837  ops/ms
ClientPb.getUser                         thrpt       3  12.707 ± 0.835  ops/ms
ClientPb.listUser                        thrpt       3  10.713 ± 0.870  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.497   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.145   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.108   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.126   ms/op
ClientPb.createUser                     sample  380341   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.683           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.137           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.204           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  387171   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.782           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.767           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.795           ms/op
ClientPb.getUser                        sample  380142   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.884           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.761           ms/op
ClientPb.listUser                       sample  314959   3.045 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.346           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.681           ms/op
