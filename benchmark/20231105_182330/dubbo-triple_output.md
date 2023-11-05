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
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 5.132 ops/ms
# Warmup Iteration   3: 8.434 ops/ms
Iteration   1: 8.698 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.980 ±(99.9%) 4.619 ops/ms [Average]
  (min, avg, max) = (8.698, 8.980, 9.188), stdev = 0.253
  CI (99.9%): [4.360, 13.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 9.509 ops/ms
Iteration   2: 9.611 ops/ms
Iteration   3: 9.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (9.509, 9.585, 9.635), stdev = 0.067
  CI (99.9%): [8.367, 10.803] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.627 ops/ms
Iteration   1: 8.936 ops/ms
Iteration   2: 8.881 ops/ms
Iteration   3: 8.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.926 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (8.881, 8.926, 8.961), stdev = 0.041
  CI (99.9%): [8.179, 9.672] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 7.042 ops/ms
# Warmup Iteration   3: 7.275 ops/ms
Iteration   1: 7.408 ops/ms
Iteration   2: 7.508 ops/ms
Iteration   3: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.525 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (7.408, 7.525, 7.658), stdev = 0.125
  CI (99.9%): [5.237, 9.813] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.944 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.005 ms/op
Iteration   1: 3.573 ±(99.9%) 0.004 ms/op
Iteration   2: 3.490 ±(99.9%) 0.004 ms/op
Iteration   3: 3.569 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.544 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.490, 3.544, 3.573), stdev = 0.047
  CI (99.9%): [2.693, 4.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.122 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.005 ms/op
Iteration   1: 3.418 ±(99.9%) 0.005 ms/op
Iteration   2: 3.410 ±(99.9%) 0.003 ms/op
Iteration   3: 3.426 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.418 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.410, 3.418, 3.426), stdev = 0.008
  CI (99.9%): [3.280, 3.556] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.130 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.003 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
Iteration   3: 3.552 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.539 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.527, 3.539, 3.552), stdev = 0.013
  CI (99.9%): [3.307, 3.772] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.842 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.009 ms/op
Iteration   1: 4.139 ±(99.9%) 0.004 ms/op
Iteration   2: 4.111 ±(99.9%) 0.010 ms/op
Iteration   3: 4.184 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.145 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.111, 4.145, 4.184), stdev = 0.037
  CI (99.9%): [3.477, 4.812] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.314 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.010 ms/op
Iteration   1: 3.783 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 30.709 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   2: 3.537 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  22.729 ms/op
                 createUser·p0.9999: 31.061 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 3.635 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.127 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  24.771 ms/op
                 createUser·p0.9999: 34.341 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263171
  mean =      3.649 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2202 
    [ 2.500,  5.000) = 251391 
    [ 5.000,  7.500) = 6751 
    [ 7.500, 10.000) = 2015 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     22.838 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     34.627 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.337 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.009 ms/op
Iteration   1: 3.497 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 3.538 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 27.390 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.536 ms/op
                 existUser·p0.999:  16.269 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271858
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5322 
    [ 2.500,  5.000) = 260327 
    [ 5.000,  7.500) = 4886 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 108 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     27.060 ms/op
     p(99.9990) =     28.419 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.090 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.012 ms/op
Iteration   1: 3.601 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  20.028 ms/op
                 getUser·p0.9999: 22.745 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.518 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.942 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   3: 3.587 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  13.582 ms/op
                 getUser·p0.9999: 28.285 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268656
  mean =      3.569 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2130 
    [ 2.500,  5.000) = 260383 
    [ 5.000,  7.500) = 4719 
    [ 7.500, 10.000) = 951 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     16.085 ms/op
     p(99.9900) =     27.464 ms/op
     p(99.9990) =     29.398 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.419 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.012 ms/op
Iteration   1: 4.245 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  20.501 ms/op
                 listUser·p0.9999: 23.540 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.229 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 17.831 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 4.216 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  15.141 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226917
  mean =      4.230 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 214938 
    [ 5.000,  7.500) = 9616 
    [ 7.500, 10.000) = 1625 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     16.058 ms/op
     p(99.9900) =     22.673 ms/op
     p(99.9990) =     24.311 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.980 ± 4.619  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 1.218  ops/ms
ClientPb.getUser                         thrpt       3   8.926 ± 0.747  ops/ms
ClientPb.listUser                        thrpt       3   7.525 ± 2.288  ops/ms
ClientPb.createUser                       avgt       3   3.544 ± 0.851   ms/op
ClientPb.existUser                        avgt       3   3.418 ± 0.138   ms/op
ClientPb.getUser                          avgt       3   3.539 ± 0.232   ms/op
ClientPb.listUser                         avgt       3   4.145 ± 0.668   ms/op
ClientPb.createUser                     sample  263171   3.649 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.838           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.031           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  271858   3.529 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.333           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.060           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  268656   3.569 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.464           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  226917   4.230 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.412           ms/op
