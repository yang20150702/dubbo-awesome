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
# Warmup Iteration   1: 4.065 ops/ms
# Warmup Iteration   2: 11.835 ops/ms
# Warmup Iteration   3: 12.210 ops/ms
Iteration   1: 12.611 ops/ms
Iteration   2: 12.402 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.539 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (12.402, 12.539, 12.611), stdev = 0.119
  CI (99.9%): [10.376, 14.702] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.494 ops/ms
# Warmup Iteration   2: 13.183 ops/ms
# Warmup Iteration   3: 13.305 ops/ms
Iteration   1: 13.171 ops/ms
Iteration   2: 13.226 ops/ms
Iteration   3: 13.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.211 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (13.171, 13.211, 13.237), stdev = 0.035
  CI (99.9%): [12.566, 13.857] (assumes normal distribution)


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
# Warmup Iteration   1: 7.776 ops/ms
# Warmup Iteration   2: 12.827 ops/ms
# Warmup Iteration   3: 12.966 ops/ms
Iteration   1: 13.120 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 12.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.978 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (12.846, 12.978, 13.120), stdev = 0.137
  CI (99.9%): [10.475, 15.481] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ops/ms
# Warmup Iteration   2: 10.500 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (10.662, 10.709, 10.783), stdev = 0.065
  CI (99.9%): [9.522, 11.896] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.540, 2.549, 2.558), stdev = 0.009
  CI (99.9%): [2.385, 2.713] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.440, 2.448, 2.458), stdev = 0.009
  CI (99.9%): [2.282, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.468, 2.478, 2.488), stdev = 0.010
  CI (99.9%): [2.296, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (2.984, 2.987, 2.988), stdev = 0.002
  CI (99.9%): [2.949, 3.024] (assumes normal distribution)


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.029 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.949 ms/op
                 createUser·p0.9999: 12.468 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 10.539 ms/op
                 createUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381499
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 183902 
    [ 2.500,  3.750) = 193801 
    [ 3.750,  5.000) = 3117 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     13.383 ms/op
     p(99.9990) =     14.332 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.832 ms/op
                 existUser·p0.9999: 13.545 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 13.807 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  8.002 ms/op
                 existUser·p0.9999: 11.059 ms/op
                 existUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391652
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 195447 
    [ 2.500,  3.750) = 193130 
    [ 3.750,  5.000) = 2254 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      7.738 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.093 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  6.355 ms/op
                 getUser·p0.9999: 14.240 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.439 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  5.959 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388740
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 195463 
    [ 2.500,  3.750) = 189464 
    [ 3.750,  5.000) = 3121 
    [ 5.000,  6.250) = 232 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.124 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.930 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 10.437 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.193 ms/op
                 listUser·p0.9999: 10.942 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.960 ms/op
                 listUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318926
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 92425 
    [ 2.500,  3.750) = 187366 
    [ 3.750,  5.000) = 32131 
    [ 5.000,  6.250) = 5617 
    [ 6.250,  7.500) = 624 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.176 ms/op
     p(99.9900) =     11.895 ms/op
     p(99.9990) =     13.055 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.539 ± 2.163  ops/ms
ClientPb.existUser                       thrpt       3  13.211 ± 0.646  ops/ms
ClientPb.getUser                         thrpt       3  12.978 ± 2.503  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 1.187  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.182   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.038   ms/op
ClientPb.createUser                     sample  381499   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.536           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.383           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  391652   2.448 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.738           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.172           ms/op
ClientPb.getUser                        sample  388740   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.904           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.124           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  318926   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.176           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.895           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.943           ms/op
