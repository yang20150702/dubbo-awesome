# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.046 ops/ms
# Warmup Iteration   2: 12.002 ops/ms
# Warmup Iteration   3: 12.593 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.733 ops/ms
Iteration   3: 12.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (12.601, 12.648, 12.733), stdev = 0.074
  CI (99.9%): [11.297, 13.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.886 ops/ms
# Warmup Iteration   2: 13.236 ops/ms
# Warmup Iteration   3: 13.107 ops/ms
Iteration   1: 13.176 ops/ms
Iteration   2: 13.293 ops/ms
Iteration   3: 13.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.224 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (13.176, 13.224, 13.293), stdev = 0.061
  CI (99.9%): [12.107, 14.341] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.714 ops/ms
# Warmup Iteration   2: 12.629 ops/ms
# Warmup Iteration   3: 12.803 ops/ms
Iteration   1: 12.905 ops/ms
Iteration   2: 12.996 ops/ms
Iteration   3: 12.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.945 ±(99.9%) 0.851 ops/ms [Average]
  (min, avg, max) = (12.905, 12.945, 12.996), stdev = 0.047
  CI (99.9%): [12.095, 13.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.749 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.657 ±(99.9%) 0.163 ops/ms [Average]
  (min, avg, max) = (10.647, 10.657, 10.665), stdev = 0.009
  CI (99.9%): [10.494, 10.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.468, 2.478, 2.486), stdev = 0.010
  CI (99.9%): [2.304, 2.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.006 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.464, 2.470, 2.477), stdev = 0.006
  CI (99.9%): [2.355, 2.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.003 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.511, 2.528, 2.539), stdev = 0.015
  CI (99.9%): [2.260, 2.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.940 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.005 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.990, 3.003, 3.025), stdev = 0.019
  CI (99.9%): [2.653, 3.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  11.170 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  9.389 ms/op
                 createUser·p0.9999: 13.111 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  7.692 ms/op
                 createUser·p0.9999: 10.979 ms/op
                 createUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385034
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 187472 
    [ 2.500,  3.750) = 193514 
    [ 3.750,  5.000) = 3108 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.880 ms/op
     p(99.9900) =     13.132 ms/op
     p(99.9990) =     14.210 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.206 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  8.008 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 12.325 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386591
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 191805 
    [ 2.500,  3.750) = 190978 
    [ 3.750,  5.000) = 2645 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.981 ms/op
     p(99.9900) =     13.359 ms/op
     p(99.9990) =     13.939 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  11.826 ms/op
                 getUser·p0.9999: 14.310 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  9.089 ms/op
                 getUser·p0.9999: 13.914 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.535 ms/op
                 getUser·p0.999:  7.277 ms/op
                 getUser·p0.9999: 11.963 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380174
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187595 
    [ 2.500,  3.750) = 188401 
    [ 3.750,  5.000) = 3144 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.729 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     14.936 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.009 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 11.249 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.955 ms/op
                 listUser·p1.00:   13.025 ms/op

Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.856 ms/op
                 listUser·p0.9999: 13.705 ms/op
                 listUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321470
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 96599 
    [ 2.500,  3.750) = 187079 
    [ 3.750,  5.000) = 30751 
    [ 5.000,  6.250) = 5563 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.789 ms/op
     p(99.9990) =     14.296 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 1.351  ops/ms
ClientPb.existUser                       thrpt       3  13.224 ± 1.117  ops/ms
ClientPb.getUser                         thrpt       3  12.945 ± 0.851  ops/ms
ClientPb.listUser                        thrpt       3  10.657 ± 0.163  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.175   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.115   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.268   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.350   ms/op
ClientPb.createUser                     sample  385034   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.132           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  386591   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.981           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.359           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  380174   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.920           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.959           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  321470   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.627           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.789           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.647           ms/op
