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
# Warmup Iteration   1: 4.456 ops/ms
# Warmup Iteration   2: 11.996 ops/ms
# Warmup Iteration   3: 12.299 ops/ms
Iteration   1: 12.432 ops/ms
Iteration   2: 12.525 ops/ms
Iteration   3: 12.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.510 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (12.432, 12.510, 12.573), stdev = 0.072
  CI (99.9%): [11.206, 13.815] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.565 ops/ms
# Warmup Iteration   2: 12.956 ops/ms
# Warmup Iteration   3: 12.818 ops/ms
Iteration   1: 12.780 ops/ms
Iteration   2: 13.071 ops/ms
Iteration   3: 12.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.930 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (12.780, 12.930, 13.071), stdev = 0.146
  CI (99.9%): [10.274, 15.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.143 ops/ms
# Warmup Iteration   2: 12.437 ops/ms
# Warmup Iteration   3: 12.708 ops/ms
Iteration   1: 12.643 ops/ms
Iteration   2: 12.670 ops/ms
Iteration   3: 12.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.702 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (12.643, 12.702, 12.792), stdev = 0.079
  CI (99.9%): [11.258, 14.145] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.146 ops/ms
# Warmup Iteration   2: 10.377 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (10.520, 10.564, 10.647), stdev = 0.072
  CI (99.9%): [9.252, 11.876] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.541, 2.557, 2.574), stdev = 0.016
  CI (99.9%): [2.261, 2.853] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.445, 2.453, 2.463), stdev = 0.009
  CI (99.9%): [2.290, 2.617] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (2.501, 2.531, 2.552), stdev = 0.026
  CI (99.9%): [2.052, 3.010] (assumes normal distribution)


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
# Warmup Iteration   1: 5.073 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
Iteration   2: 3.004 ±(99.9%) 0.004 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.004, 3.029, 3.043), stdev = 0.021
  CI (99.9%): [2.637, 3.420] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.358 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  12.557 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  9.939 ms/op
                 createUser·p0.9999: 12.026 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  8.205 ms/op
                 createUser·p0.9999: 10.610 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379461
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 180874 
    [ 2.500,  3.750) = 193817 
    [ 3.750,  5.000) = 3780 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      9.249 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.094 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 14.159 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  9.292 ms/op
                 existUser·p0.9999: 13.826 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383354
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 184603 
    [ 2.500,  3.750) = 194350 
    [ 3.750,  5.000) = 3292 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      7.949 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.508 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  12.978 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  10.199 ms/op
                 getUser·p0.9999: 13.173 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 13.781 ms/op
                 getUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376877
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 184034 
    [ 2.500,  3.750) = 186346 
    [ 3.750,  5.000) = 4902 
    [ 5.000,  6.250) = 1035 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     15.110 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.280 ms/op
                 listUser·p0.9999: 11.165 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.758 ms/op
                 listUser·p0.9999: 11.115 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 18.135 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316587
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 87995 
    [ 2.500,  3.750) = 188245 
    [ 3.750,  5.000) = 32655 
    [ 5.000,  6.250) = 6199 
    [ 6.250,  7.500) = 701 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     17.401 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.510 ± 1.305  ops/ms
ClientPb.existUser                       thrpt       3  12.930 ± 2.656  ops/ms
ClientPb.getUser                         thrpt       3  12.702 ± 1.443  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 1.312  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.296   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.479   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.391   ms/op
ClientPb.createUser                     sample  379461   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.249           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  383354   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.800           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.949           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  376877   2.545 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.368           ms/op
ClientPb.listUser                       sample  316587   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.738           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.401           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.235           ms/op
