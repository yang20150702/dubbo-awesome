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
# Warmup Iteration   1: 5.200 ops/ms
# Warmup Iteration   2: 12.214 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 12.985 ops/ms
Iteration   2: 13.055 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.011 ±(99.9%) 0.710 ops/ms [Average]
  (min, avg, max) = (12.985, 13.011, 13.055), stdev = 0.039
  CI (99.9%): [12.301, 13.721] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.387 ops/ms
# Warmup Iteration   2: 13.152 ops/ms
# Warmup Iteration   3: 13.283 ops/ms
Iteration   1: 13.380 ops/ms
Iteration   2: 13.216 ops/ms
Iteration   3: 13.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.266 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (13.202, 13.266, 13.380), stdev = 0.099
  CI (99.9%): [11.457, 15.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ops/ms
# Warmup Iteration   2: 12.783 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 12.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.972 ±(99.9%) 1.485 ops/ms [Average]
  (min, avg, max) = (12.924, 12.972, 13.066), stdev = 0.081
  CI (99.9%): [11.487, 14.457] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.850 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.706 ops/ms
Iteration   1: 10.763 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.696 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (10.629, 10.696, 10.763), stdev = 0.067
  CI (99.9%): [9.468, 11.923] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.445 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.434, 2.445, 2.454), stdev = 0.010
  CI (99.9%): [2.257, 2.632] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.003 ms/op
Iteration   3: 2.395 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.413 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.395, 2.413, 2.431), stdev = 0.018
  CI (99.9%): [2.086, 2.740] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.435 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.424, 2.435, 2.444), stdev = 0.010
  CI (99.9%): [2.255, 2.616] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.005 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
Iteration   3: 2.934 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.931 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.918, 2.931, 2.939), stdev = 0.011
  CI (99.9%): [2.733, 3.128] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  11.029 ms/op
                 createUser·p0.9999: 13.618 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.733 ms/op
                 createUser·p0.9999: 13.177 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 10.617 ms/op
                 createUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385434
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 187560 
    [ 2.500,  3.750) = 193852 
    [ 3.750,  5.000) = 3214 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 141 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      9.053 ms/op
     p(99.9900) =     13.475 ms/op
     p(99.9990) =     14.294 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  5.797 ms/op
                 existUser·p0.9999: 14.467 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 2.382 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.400 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.136 ms/op
                 existUser·p0.9999: 12.848 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   3: 2.365 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  5.341 ms/op
                 existUser·p0.9999: 11.403 ms/op
                 existUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402100
  mean =      2.385 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 211679 
    [ 2.500,  3.750) = 187775 
    [ 3.750,  5.000) = 2062 
    [ 5.000,  6.250) = 150 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =      5.300 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     15.168 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  7.914 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  6.979 ms/op
                 getUser·p0.9999: 11.993 ms/op
                 getUser·p1.00:   12.599 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  5.860 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390112
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 198125 
    [ 2.500,  3.750) = 187492 
    [ 3.750,  5.000) = 3663 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      7.640 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.009 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 12.036 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.739 ms/op
                 listUser·p0.9999: 13.177 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.293 ms/op
                 listUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322017
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 96157 
    [ 2.500,  3.750) = 188385 
    [ 3.750,  5.000) = 30388 
    [ 5.000,  6.250) = 5736 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.584 ms/op
     p(99.9900) =     12.697 ms/op
     p(99.9990) =     13.446 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.011 ± 0.710  ops/ms
ClientPb.existUser                       thrpt       3  13.266 ± 1.810  ops/ms
ClientPb.getUser                         thrpt       3  12.972 ± 1.485  ops/ms
ClientPb.listUser                        thrpt       3  10.696 ± 1.227  ops/ms
ClientPb.createUser                       avgt       3   2.445 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   2.413 ± 0.327   ms/op
ClientPb.getUser                          avgt       3   2.435 ± 0.180   ms/op
ClientPb.listUser                         avgt       3   2.931 ± 0.197   ms/op
ClientPb.createUser                     sample  385434   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.053           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.475           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  402100   2.385 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.952           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.254           ms/op
ClientPb.getUser                        sample  390112   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.674           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.640           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.091           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  322017   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.584           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.697           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
