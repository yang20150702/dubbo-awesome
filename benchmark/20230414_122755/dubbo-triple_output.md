# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.764 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 9.460 ops/ms
Iteration   2: 9.513 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.470 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (9.437, 9.470, 9.513), stdev = 0.039
  CI (99.9%): [8.764, 10.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 9.327 ops/ms
# Warmup Iteration   3: 9.483 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 9.802 ops/ms
Iteration   3: 9.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.768 ±(99.9%) 3.303 ops/ms [Average]
  (min, avg, max) = (9.573, 9.768, 9.930), stdev = 0.181
  CI (99.9%): [6.465, 13.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 8.243 ops/ms
# Warmup Iteration   3: 8.862 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.409 ops/ms
Iteration   3: 9.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.325 ±(99.9%) 2.014 ops/ms [Average]
  (min, avg, max) = (9.200, 9.325, 9.409), stdev = 0.110
  CI (99.9%): [7.310, 11.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 7.386 ops/ms
# Warmup Iteration   3: 7.872 ops/ms
Iteration   1: 7.946 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.212 ±(99.9%) 4.450 ops/ms [Average]
  (min, avg, max) = (7.946, 8.212, 8.424), stdev = 0.244
  CI (99.9%): [3.762, 12.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.410 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.008 ms/op
Iteration   1: 3.359 ±(99.9%) 0.006 ms/op
Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
Iteration   3: 3.337 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.349 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (3.337, 3.349, 3.359), stdev = 0.011
  CI (99.9%): [3.147, 3.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.370 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.213 ±(99.9%) 0.003 ms/op
Iteration   2: 3.218 ±(99.9%) 0.010 ms/op
Iteration   3: 3.189 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.207 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.189, 3.207, 3.218), stdev = 0.015
  CI (99.9%): [2.927, 3.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.003 ms/op
Iteration   1: 3.443 ±(99.9%) 0.011 ms/op
Iteration   2: 3.495 ±(99.9%) 0.004 ms/op
Iteration   3: 3.284 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 2.001 ms/op [Average]
  (min, avg, max) = (3.284, 3.407, 3.495), stdev = 0.110
  CI (99.9%): [1.406, 5.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.760 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.006 ms/op
Iteration   1: 3.891 ±(99.9%) 0.015 ms/op
Iteration   2: 4.020 ±(99.9%) 0.005 ms/op
Iteration   3: 3.958 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.891, 3.956, 4.020), stdev = 0.064
  CI (99.9%): [2.781, 5.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.242 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.595 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   7.712 ms/op
                 createUser·p0.999:  20.910 ms/op
                 createUser·p0.9999: 28.516 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  21.190 ms/op
                 createUser·p0.9999: 24.409 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 24.867 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273030
  mean =      3.516 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6756 
    [ 2.500,  5.000) = 256692 
    [ 5.000,  7.500) = 7430 
    [ 7.500, 10.000) = 1672 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     26.689 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.139 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
Iteration   1: 3.241 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 23.663 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  19.653 ms/op
                 existUser·p0.9999: 23.812 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  12.545 ms/op
                 existUser·p0.9999: 26.403 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289389
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9639 
    [ 2.500,  5.000) = 273886 
    [ 5.000,  7.500) = 4750 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     12.551 ms/op
     p(99.9900) =     24.512 ms/op
     p(99.9990) =     27.103 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.993 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.011 ms/op
Iteration   1: 3.533 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  19.640 ms/op
                 getUser·p0.9999: 27.937 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  23.593 ms/op
                 getUser·p0.9999: 29.835 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 3.411 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.689 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 25.895 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276741
  mean =      3.465 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5294 
    [ 2.500,  5.000) = 262829 
    [ 5.000,  7.500) = 7212 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     19.538 ms/op
     p(99.9900) =     28.388 ms/op
     p(99.9990) =     30.687 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.221 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.012 ms/op
Iteration   1: 3.877 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  19.220 ms/op
                 listUser·p0.9999: 21.979 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.180 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 19.955 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.953 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.141 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243375
  mean =      3.942 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 234765 
    [ 5.000,  7.500) = 6651 
    [ 7.500, 10.000) = 1202 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.083 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     22.366 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.470 ± 0.705  ops/ms
ClientPb.existUser                       thrpt       3   9.768 ± 3.303  ops/ms
ClientPb.getUser                         thrpt       3   9.325 ± 2.014  ops/ms
ClientPb.listUser                        thrpt       3   8.212 ± 4.450  ops/ms
ClientPb.createUser                       avgt       3   3.349 ± 0.202   ms/op
ClientPb.existUser                        avgt       3   3.207 ± 0.279   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 2.001   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 1.176   ms/op
ClientPb.createUser                     sample  273030   3.516 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.689           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  289389   3.315 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.384           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.427           ms/op
ClientPb.getUser                        sample  276741   3.465 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.538           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  243375   3.942 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.407           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.083           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.201           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.643           ms/op
