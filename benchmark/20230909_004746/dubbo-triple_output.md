# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.612 ops/ms
# Warmup Iteration   2: 6.572 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.669 ±(99.9%) 4.330 ops/ms [Average]
  (min, avg, max) = (9.485, 9.669, 9.937), stdev = 0.237
  CI (99.9%): [5.339, 13.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ops/ms
# Warmup Iteration   2: 9.077 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.194 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (9.991, 10.194, 10.338), stdev = 0.181
  CI (99.9%): [6.897, 13.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 8.845 ops/ms
# Warmup Iteration   3: 9.724 ops/ms
Iteration   1: 9.958 ops/ms
Iteration   2: 10.065 ops/ms
Iteration   3: 9.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.860 ±(99.9%) 4.894 ops/ms [Average]
  (min, avg, max) = (9.556, 9.860, 10.065), stdev = 0.268
  CI (99.9%): [4.966, 14.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 7.518 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.202 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (8.072, 8.202, 8.389), stdev = 0.166
  CI (99.9%): [5.171, 11.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.642 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.004 ms/op
Iteration   1: 3.330 ±(99.9%) 0.004 ms/op
Iteration   2: 3.447 ±(99.9%) 0.009 ms/op
Iteration   3: 3.364 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (3.330, 3.381, 3.447), stdev = 0.060
  CI (99.9%): [2.282, 4.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.227 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.195 ±(99.9%) 0.007 ms/op
Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
Iteration   3: 3.263 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.227 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.195, 3.227, 3.263), stdev = 0.034
  CI (99.9%): [2.606, 3.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.005 ms/op
Iteration   1: 3.339 ±(99.9%) 0.004 ms/op
Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.356 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.331, 3.356, 3.399), stdev = 0.037
  CI (99.9%): [2.682, 4.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.500 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.004 ms/op
Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
Iteration   2: 3.800 ±(99.9%) 0.008 ms/op
Iteration   3: 3.820 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.839 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.800, 3.839, 3.896), stdev = 0.051
  CI (99.9%): [2.917, 4.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.668 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.010 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.000 ms/op
                 createUser·p0.999:  18.823 ms/op
                 createUser·p0.9999: 23.190 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  18.981 ms/op
                 createUser·p0.9999: 25.178 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  17.912 ms/op
                 createUser·p0.9999: 21.742 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282252
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21493 
    [ 2.500,  5.000) = 251728 
    [ 5.000,  7.500) = 7669 
    [ 7.500, 10.000) = 921 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     18.104 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 20.441 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.190 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   4.183 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  12.550 ms/op
                 existUser·p0.9999: 27.589 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 22.127 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303442
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13987 
    [ 2.500,  5.000) = 282968 
    [ 5.000,  7.500) = 5268 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     12.510 ms/op
     p(99.9900) =     26.039 ms/op
     p(99.9990) =     27.852 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.864 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.013 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 23.531 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.632 ms/op
                 getUser·p0.9999: 31.490 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 22.908 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291654
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7983 
    [ 2.500,  5.000) = 276678 
    [ 5.000,  7.500) = 5712 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     11.646 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     32.154 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.988 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.015 ms/op
Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.962 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 26.170 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 3.865 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.854 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 15.057 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247422
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 236282 
    [ 5.000,  7.500) = 7995 
    [ 7.500, 10.000) = 2339 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.871 ms/op
     p(99.9000) =     14.903 ms/op
     p(99.9900) =     25.110 ms/op
     p(99.9990) =     26.432 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.669 ± 4.330  ops/ms
ClientPb.existUser                       thrpt       3  10.194 ± 3.297  ops/ms
ClientPb.getUser                         thrpt       3   9.860 ± 4.894  ops/ms
ClientPb.listUser                        thrpt       3   8.202 ± 3.031  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 1.099   ms/op
ClientPb.existUser                        avgt       3   3.227 ± 0.621   ms/op
ClientPb.getUser                          avgt       3   3.356 ± 0.674   ms/op
ClientPb.listUser                         avgt       3   3.839 ± 0.922   ms/op
ClientPb.createUser                     sample  282252   3.399 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.998           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.104           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  303442   3.163 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.721           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.510           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.017           ms/op
ClientPb.getUser                        sample  291654   3.288 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.186           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.646           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.721           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  247422   3.877 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.221           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.871           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.903           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
