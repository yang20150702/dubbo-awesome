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
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 5.990 ops/ms
# Warmup Iteration   3: 8.452 ops/ms
Iteration   1: 8.886 ops/ms
Iteration   2: 8.967 ops/ms
Iteration   3: 9.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.028 ±(99.9%) 3.290 ops/ms [Average]
  (min, avg, max) = (8.886, 9.028, 9.231), stdev = 0.180
  CI (99.9%): [5.738, 12.318] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 8.354 ops/ms
# Warmup Iteration   3: 9.187 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.355 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.355 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (9.273, 9.355, 9.437), stdev = 0.082
  CI (99.9%): [7.854, 10.857] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.446 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 9.053 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.127 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (9.081, 9.127, 9.186), stdev = 0.053
  CI (99.9%): [8.152, 10.102] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.426 ops/ms
# Warmup Iteration   2: 7.002 ops/ms
# Warmup Iteration   3: 7.459 ops/ms
Iteration   1: 7.718 ops/ms
Iteration   2: 7.728 ops/ms
Iteration   3: 7.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.644 ±(99.9%) 2.507 ops/ms [Average]
  (min, avg, max) = (7.485, 7.644, 7.728), stdev = 0.137
  CI (99.9%): [5.137, 10.151] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.125 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.006 ms/op
Iteration   1: 3.568 ±(99.9%) 0.005 ms/op
Iteration   2: 3.641 ±(99.9%) 0.005 ms/op
Iteration   3: 3.596 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.602 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (3.568, 3.602, 3.641), stdev = 0.037
  CI (99.9%): [2.932, 4.272] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.918 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.006 ms/op
Iteration   1: 3.410 ±(99.9%) 0.004 ms/op
Iteration   2: 3.413 ±(99.9%) 0.005 ms/op
Iteration   3: 3.391 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.405 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (3.391, 3.405, 3.413), stdev = 0.012
  CI (99.9%): [3.181, 3.629] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.164 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.002 ms/op
Iteration   1: 3.535 ±(99.9%) 0.004 ms/op
Iteration   2: 3.544 ±(99.9%) 0.004 ms/op
Iteration   3: 3.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.536 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.529, 3.536, 3.544), stdev = 0.008
  CI (99.9%): [3.396, 3.676] (assumes normal distribution)


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
# Warmup Iteration   1: 10.990 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.008 ms/op
Iteration   1: 4.174 ±(99.9%) 0.006 ms/op
Iteration   2: 4.110 ±(99.9%) 0.012 ms/op
Iteration   3: 4.165 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.149 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (4.110, 4.149, 4.174), stdev = 0.035
  CI (99.9%): [3.516, 4.783] (assumes normal distribution)


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
# Warmup Iteration   1: 9.954 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.012 ms/op
Iteration   1: 3.736 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  17.378 ms/op
                 createUser·p0.9999: 30.339 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   2: 3.547 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  23.947 ms/op
                 createUser·p0.9999: 27.753 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   3: 3.492 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  25.482 ms/op
                 createUser·p0.9999: 29.885 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267457
  mean =      3.589 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4442 
    [ 2.500,  5.000) = 252123 
    [ 5.000,  7.500) = 8751 
    [ 7.500, 10.000) = 1498 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     22.532 ms/op
     p(99.9900) =     29.336 ms/op
     p(99.9990) =     31.632 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 10.547 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.009 ms/op
Iteration   1: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  20.918 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  23.061 ms/op
                 existUser·p0.9999: 25.602 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  11.921 ms/op
                 existUser·p0.9999: 27.651 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281722
  mean =      3.410 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6909 
    [ 2.500,  5.000) = 268807 
    [ 5.000,  7.500) = 4883 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     26.242 ms/op
     p(99.9990) =     27.925 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.535 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.011 ms/op
Iteration   1: 3.663 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.648 ms/op
                 getUser·p0.999:  12.916 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.561 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.352 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  19.174 ms/op
                 getUser·p0.9999: 24.314 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.534 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  20.300 ms/op
                 getUser·p0.9999: 25.033 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267676
  mean =      3.585 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2454 
    [ 2.500,  5.000) = 256874 
    [ 5.000,  7.500) = 6723 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.524 ms/op
     p(99.9900) =     24.362 ms/op
     p(99.9990) =     25.558 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.013 ms/op
Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  22.278 ms/op
                 listUser·p0.9999: 26.329 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 4.226 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.752 ms/op
                 listUser·p0.9999: 17.807 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.254 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.496 ms/op
                 listUser·p0.9999: 17.547 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225928
  mean =      4.245 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 216020 
    [ 5.000,  7.500) = 7948 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     16.680 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.730 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.028 ± 3.290  ops/ms
ClientPb.existUser                       thrpt       3   9.355 ± 1.502  ops/ms
ClientPb.getUser                         thrpt       3   9.127 ± 0.975  ops/ms
ClientPb.listUser                        thrpt       3   7.644 ± 2.507  ops/ms
ClientPb.createUser                       avgt       3   3.602 ± 0.670   ms/op
ClientPb.existUser                        avgt       3   3.405 ± 0.224   ms/op
ClientPb.getUser                          avgt       3   3.536 ± 0.140   ms/op
ClientPb.listUser                         avgt       3   4.149 ± 0.634   ms/op
ClientPb.createUser                     sample  267457   3.589 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.532           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  281722   3.410 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.242           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.000           ms/op
ClientPb.getUser                        sample  267676   3.585 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.524           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.362           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  225928   4.245 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.487           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
