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
# Warmup Iteration   1: 4.542 ops/ms
# Warmup Iteration   2: 12.110 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.802 ±(99.9%) 0.678 ops/ms [Average]
  (min, avg, max) = (12.772, 12.802, 12.844), stdev = 0.037
  CI (99.9%): [12.124, 13.480] (assumes normal distribution)


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
# Warmup Iteration   1: 8.366 ops/ms
# Warmup Iteration   2: 12.991 ops/ms
# Warmup Iteration   3: 13.166 ops/ms
Iteration   1: 13.247 ops/ms
Iteration   2: 13.324 ops/ms
Iteration   3: 13.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.292 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (13.247, 13.292, 13.324), stdev = 0.040
  CI (99.9%): [12.560, 14.023] (assumes normal distribution)


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
# Warmup Iteration   1: 8.232 ops/ms
# Warmup Iteration   2: 12.820 ops/ms
# Warmup Iteration   3: 13.131 ops/ms
Iteration   1: 13.184 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.052 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (12.907, 13.052, 13.184), stdev = 0.139
  CI (99.9%): [10.521, 15.584] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.443 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.675 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.691 ±(99.9%) 0.834 ops/ms [Average]
  (min, avg, max) = (10.655, 10.691, 10.742), stdev = 0.046
  CI (99.9%): [9.857, 11.525] (assumes normal distribution)


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.475 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.466, 2.475, 2.492), stdev = 0.014
  CI (99.9%): [2.218, 2.733] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.418 ±(99.9%) 0.003 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.418, 2.438, 2.459), stdev = 0.021
  CI (99.9%): [2.063, 2.813] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.439 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.430, 2.439, 2.450), stdev = 0.010
  CI (99.9%): [2.252, 2.626] (assumes normal distribution)


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.043 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (3.033, 3.043, 3.060), stdev = 0.015
  CI (99.9%): [2.771, 3.315] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  12.280 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 12.826 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  7.949 ms/op
                 createUser·p0.9999: 14.702 ms/op
                 createUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377587
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 182982 
    [ 2.500,  3.750) = 190373 
    [ 3.750,  5.000) = 3074 
    [ 5.000,  6.250) = 538 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.657 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     15.179 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.959 ms/op
                 existUser·p0.9999: 13.727 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  6.304 ms/op
                 existUser·p0.9999: 13.029 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.218 ms/op
                 existUser·p0.9999: 12.465 ms/op
                 existUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397468
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 199479 
    [ 2.500,  3.750) = 195290 
    [ 3.750,  5.000) = 2029 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      6.140 ms/op
     p(99.9900) =     13.193 ms/op
     p(99.9990) =     13.829 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  10.648 ms/op
                 getUser·p0.9999: 13.705 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.606 ms/op
                 getUser·p0.9999: 12.767 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  5.378 ms/op
                 getUser·p0.9999: 11.714 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386829
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 193681 
    [ 2.500,  3.750) = 186839 
    [ 3.750,  5.000) = 4831 
    [ 5.000,  6.250) = 937 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =     13.276 ms/op
     p(99.9990) =     13.914 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.452 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.055 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.551 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319165
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 92356 
    [ 2.500,  3.750) = 187292 
    [ 3.750,  5.000) = 31811 
    [ 5.000,  6.250) = 6154 
    [ 6.250,  7.500) = 744 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.111 ms/op
     p(99.9990) =     11.864 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.802 ± 0.678  ops/ms
ClientPb.existUser                       thrpt       3  13.292 ± 0.731  ops/ms
ClientPb.getUser                         thrpt       3  13.052 ± 2.531  ops/ms
ClientPb.listUser                        thrpt       3  10.691 ± 0.834  ops/ms
ClientPb.createUser                       avgt       3   2.475 ± 0.257   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.375   ms/op
ClientPb.getUser                          avgt       3   2.439 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   3.043 ± 0.272   ms/op
ClientPb.createUser                     sample  377587   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.303           ms/op
ClientPb.existUser                      sample  397468   2.413 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  386829   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.462           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.603           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  319165   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.692           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.042           ms/op
