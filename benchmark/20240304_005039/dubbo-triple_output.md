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
# Warmup Iteration   1: 4.892 ops/ms
# Warmup Iteration   2: 12.132 ops/ms
# Warmup Iteration   3: 12.646 ops/ms
Iteration   1: 12.796 ops/ms
Iteration   2: 12.801 ops/ms
Iteration   3: 12.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.769 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (12.710, 12.769, 12.801), stdev = 0.051
  CI (99.9%): [11.832, 13.706] (assumes normal distribution)


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
# Warmup Iteration   1: 7.945 ops/ms
# Warmup Iteration   2: 13.274 ops/ms
# Warmup Iteration   3: 13.205 ops/ms
Iteration   1: 13.204 ops/ms
Iteration   2: 13.254 ops/ms
Iteration   3: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.163 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (13.031, 13.163, 13.254), stdev = 0.117
  CI (99.9%): [11.035, 15.291] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.816 ops/ms
# Warmup Iteration   3: 13.063 ops/ms
Iteration   1: 13.045 ops/ms
Iteration   2: 13.032 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.037 ±(99.9%) 0.129 ops/ms [Average]
  (min, avg, max) = (13.032, 13.037, 13.045), stdev = 0.007
  CI (99.9%): [12.908, 13.166] (assumes normal distribution)


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
# Warmup Iteration   1: 6.536 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 10.761 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.750 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.725 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (10.666, 10.725, 10.758), stdev = 0.051
  CI (99.9%): [9.794, 11.656] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.485, 2.516, 2.534), stdev = 0.027
  CI (99.9%): [2.026, 3.006] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.438, 2.451, 2.463), stdev = 0.013
  CI (99.9%): [2.222, 2.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.466 ±(99.9%) 0.020 ms/op [Average]
  (min, avg, max) = (2.465, 2.466, 2.467), stdev = 0.001
  CI (99.9%): [2.446, 2.485] (assumes normal distribution)


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
Iteration   2: 2.937 ±(99.9%) 0.007 ms/op
Iteration   3: 2.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.945 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.937, 2.945, 2.957), stdev = 0.010
  CI (99.9%): [2.756, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  11.702 ms/op
                 createUser·p0.9999: 12.981 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.371 ms/op
                 createUser·p0.9999: 12.897 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 13.120 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378810
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 182796 
    [ 2.500,  3.750) = 190905 
    [ 3.750,  5.000) = 3813 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      9.211 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.757 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 13.501 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.689 ms/op
                 existUser·p0.999:  7.280 ms/op
                 existUser·p0.9999: 12.731 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  7.344 ms/op
                 existUser·p0.9999: 11.076 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388829
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 193427 
    [ 2.500,  3.750) = 192272 
    [ 3.750,  5.000) = 2397 
    [ 5.000,  6.250) = 269 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      7.264 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.382 ms/op
                 getUser·p0.9999: 14.581 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.384 ms/op
                 getUser·p0.9999: 12.796 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.623 ms/op
                 getUser·p0.999:  6.223 ms/op
                 getUser·p0.9999: 12.517 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389489
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 195141 
    [ 2.500,  3.750) = 189760 
    [ 3.750,  5.000) = 3601 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.378 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.638 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 10.526 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.885 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.722 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 9.847 ms/op
                 listUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317853
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 88803 
    [ 2.500,  3.750) = 189563 
    [ 3.750,  5.000) = 31949 
    [ 5.000,  6.250) = 5999 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 267 
    [ 8.750, 10.000) = 329 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.473 ms/op
     p(99.9990) =     11.353 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.769 ± 0.937  ops/ms
ClientPb.existUser                       thrpt       3  13.163 ± 2.128  ops/ms
ClientPb.getUser                         thrpt       3  13.037 ± 0.129  ops/ms
ClientPb.listUser                        thrpt       3  10.725 ± 0.931  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.490   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.230   ms/op
ClientPb.getUser                          avgt       3   2.466 ± 0.020   ms/op
ClientPb.listUser                         avgt       3   2.945 ± 0.189   ms/op
ClientPb.createUser                     sample  378810   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.631           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.211           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  388829   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.264           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.779           ms/op
ClientPb.getUser                        sample  389489   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.783           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.378           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.286           ms/op
ClientPb.listUser                       sample  317853   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.473           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
