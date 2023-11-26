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
# Warmup Iteration   1: 5.030 ops/ms
# Warmup Iteration   2: 11.903 ops/ms
# Warmup Iteration   3: 12.241 ops/ms
Iteration   1: 12.405 ops/ms
Iteration   2: 12.395 ops/ms
Iteration   3: 12.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.454 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (12.395, 12.454, 12.562), stdev = 0.093
  CI (99.9%): [10.751, 14.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.189 ops/ms
# Warmup Iteration   2: 12.900 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.669 ops/ms
Iteration   3: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.801 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (12.669, 12.801, 12.868), stdev = 0.114
  CI (99.9%): [10.721, 14.880] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ops/ms
# Warmup Iteration   2: 12.207 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.645 ops/ms
Iteration   2: 12.748 ops/ms
Iteration   3: 12.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.659 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (12.585, 12.659, 12.748), stdev = 0.082
  CI (99.9%): [11.156, 14.163] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.444 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.393 ±(99.9%) 1.738 ops/ms [Average]
  (min, avg, max) = (10.291, 10.393, 10.480), stdev = 0.095
  CI (99.9%): [8.655, 12.131] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.004 ms/op
Iteration   1: 2.597 ±(99.9%) 0.003 ms/op
Iteration   2: 2.556 ±(99.9%) 0.003 ms/op
Iteration   3: 2.541 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.541, 2.565, 2.597), stdev = 0.029
  CI (99.9%): [2.034, 3.095] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.465, 2.479, 2.487), stdev = 0.012
  CI (99.9%): [2.257, 2.701] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.503, 2.508, 2.511), stdev = 0.004
  CI (99.9%): [2.435, 2.581] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.825 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (3.021, 3.023, 3.023), stdev = 0.001
  CI (99.9%): [2.997, 3.049] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.746 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.617 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  11.816 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.501 ms/op
                 createUser·p0.9999: 16.605 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 11.311 ms/op
                 createUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371097
  mean =      2.584 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 176345 
    [ 2.500,  3.750) = 189243 
    [ 3.750,  5.000) = 4185 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      8.313 ms/op
     p(99.9900) =     14.382 ms/op
     p(99.9990) =     17.115 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.934 ms/op
                 existUser·p0.999:  8.258 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  5.799 ms/op
                 existUser·p0.9999: 12.536 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388586
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 192433 
    [ 2.500,  3.750) = 191962 
    [ 3.750,  5.000) = 3187 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     13.425 ms/op
     p(99.9990) =     14.585 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  12.226 ms/op
                 getUser·p0.9999: 14.226 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  8.201 ms/op
                 getUser·p0.9999: 12.189 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379712
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 186910 
    [ 2.500,  3.750) = 187046 
    [ 3.750,  5.000) = 4374 
    [ 5.000,  6.250) = 890 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      8.803 ms/op
     p(99.9900) =     13.665 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.009 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.711 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.354 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 11.594 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.624 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315494
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 84908 
    [ 2.500,  3.750) = 189361 
    [ 3.750,  5.000) = 33648 
    [ 5.000,  6.250) = 6180 
    [ 6.250,  7.500) = 573 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 179 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.708 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     14.202 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.454 ± 1.703  ops/ms
ClientPb.existUser                       thrpt       3  12.801 ± 2.079  ops/ms
ClientPb.getUser                         thrpt       3  12.659 ± 1.504  ops/ms
ClientPb.listUser                        thrpt       3  10.393 ± 1.738  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.531   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.073   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.026   ms/op
ClientPb.createUser                     sample  371097   2.584 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.574           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.382           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.400           ms/op
ClientPb.existUser                      sample  388586   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.676           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  379712   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.837           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.803           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.665           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  315494   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.711           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.708           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.319           ms/op
