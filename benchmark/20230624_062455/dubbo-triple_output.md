# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.153 ops/ms
# Warmup Iteration   2: 5.471 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 8.947 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.110 ±(99.9%) 3.380 ops/ms [Average]
  (min, avg, max) = (8.947, 9.110, 9.312), stdev = 0.185
  CI (99.9%): [5.731, 12.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 8.588 ops/ms
# Warmup Iteration   3: 9.678 ops/ms
Iteration   1: 9.462 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.488 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (9.368, 9.488, 9.633), stdev = 0.134
  CI (99.9%): [7.042, 11.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.833 ops/ms
# Warmup Iteration   2: 8.330 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 8.906 ops/ms
Iteration   2: 9.195 ops/ms
Iteration   3: 8.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.028 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (8.906, 9.028, 9.195), stdev = 0.150
  CI (99.9%): [6.300, 11.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.663 ops/ms
# Warmup Iteration   2: 6.583 ops/ms
# Warmup Iteration   3: 7.782 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 7.868 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.975 ±(99.9%) 3.388 ops/ms [Average]
  (min, avg, max) = (7.867, 7.975, 8.189), stdev = 0.186
  CI (99.9%): [4.587, 11.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.519 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.010 ms/op
Iteration   1: 3.585 ±(99.9%) 0.007 ms/op
Iteration   2: 3.534 ±(99.9%) 0.004 ms/op
Iteration   3: 3.389 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 1.854 ms/op [Average]
  (min, avg, max) = (3.389, 3.503, 3.585), stdev = 0.102
  CI (99.9%): [1.649, 5.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.991 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.005 ms/op
Iteration   1: 3.321 ±(99.9%) 0.006 ms/op
Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
Iteration   3: 3.359 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.292, 3.324, 3.359), stdev = 0.034
  CI (99.9%): [2.705, 3.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.105 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.003 ms/op
Iteration   1: 3.596 ±(99.9%) 0.005 ms/op
Iteration   2: 3.544 ±(99.9%) 0.005 ms/op
Iteration   3: 3.422 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (3.422, 3.520, 3.596), stdev = 0.089
  CI (99.9%): [1.890, 5.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.300 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.009 ms/op
Iteration   1: 4.128 ±(99.9%) 0.010 ms/op
Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
Iteration   3: 3.862 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 2.471 ms/op [Average]
  (min, avg, max) = (3.862, 4.009, 4.128), stdev = 0.135
  CI (99.9%): [1.538, 6.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.271 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.011 ms/op
Iteration   1: 3.511 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  22.438 ms/op
                 createUser·p0.9999: 25.813 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  21.943 ms/op
                 createUser·p0.9999: 25.089 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.409 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  18.815 ms/op
                 createUser·p0.9999: 23.908 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278727
  mean =      3.444 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6060 
    [ 2.500,  5.000) = 267433 
    [ 5.000,  7.500) = 4307 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     19.178 ms/op
     p(99.9900) =     25.563 ms/op
     p(99.9990) =     26.615 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.685 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.008 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  18.520 ms/op
                 existUser·p0.9999: 34.079 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  23.315 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  17.675 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285741
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5544 
    [ 2.500,  5.000) = 274460 
    [ 5.000,  7.500) = 4945 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     17.974 ms/op
     p(99.9900) =     31.808 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.857 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.011 ms/op
Iteration   1: 3.641 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  22.675 ms/op
                 getUser·p0.9999: 29.040 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 3.485 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  21.307 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  19.141 ms/op
                 getUser·p0.9999: 28.070 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270761
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3476 
    [ 2.500,  5.000) = 256471 
    [ 5.000,  7.500) = 9455 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.614 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     28.307 ms/op
     p(99.9990) =     29.707 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.227 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.013 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  19.200 ms/op
                 listUser·p0.9999: 24.206 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 4.035 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.467 ms/op
                 listUser·p0.999:  14.578 ms/op
                 listUser·p0.9999: 15.909 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.633 ms/op
                 listUser·p0.999:  15.863 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236487
  mean =      4.058 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 226074 
    [ 5.000,  7.500) = 8079 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     15.524 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.695 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.110 ± 3.380  ops/ms
ClientPb.existUser                       thrpt       3   9.488 ± 2.445  ops/ms
ClientPb.getUser                         thrpt       3   9.028 ± 2.728  ops/ms
ClientPb.listUser                        thrpt       3   7.975 ± 3.388  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 1.854   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 0.619   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 1.630   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 2.471   ms/op
ClientPb.createUser                     sample  278727   3.444 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.178           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.563           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  285741   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.174           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.808           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  270761   3.543 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.614           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.409           ms/op
ClientPb.listUser                       sample  236487   4.058 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.524           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.036           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
