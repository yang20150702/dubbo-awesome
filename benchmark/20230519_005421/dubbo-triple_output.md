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
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 5.209 ops/ms
# Warmup Iteration   3: 8.450 ops/ms
Iteration   1: 8.902 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.018 ±(99.9%) 3.348 ops/ms [Average]
  (min, avg, max) = (8.902, 9.018, 9.229), stdev = 0.183
  CI (99.9%): [5.670, 12.365] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 9.000 ops/ms
# Warmup Iteration   3: 9.509 ops/ms
Iteration   1: 9.536 ops/ms
Iteration   2: 9.330 ops/ms
Iteration   3: 9.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.510 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (9.330, 9.510, 9.664), stdev = 0.168
  CI (99.9%): [6.439, 12.581] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 8.814 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 9.072 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 9.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.372 ±(99.9%) 4.750 ops/ms [Average]
  (min, avg, max) = (9.072, 9.372, 9.523), stdev = 0.260
  CI (99.9%): [4.622, 14.122] (assumes normal distribution)


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
# Warmup Iteration   1: 2.451 ops/ms
# Warmup Iteration   2: 7.219 ops/ms
# Warmup Iteration   3: 7.687 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.046 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (7.913, 8.046, 8.142), stdev = 0.118
  CI (99.9%): [5.886, 10.205] (assumes normal distribution)


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
# Warmup Iteration   1: 10.658 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.005 ms/op
Iteration   1: 3.591 ±(99.9%) 0.003 ms/op
Iteration   2: 3.455 ±(99.9%) 0.009 ms/op
Iteration   3: 3.579 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.542 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.455, 3.542, 3.591), stdev = 0.075
  CI (99.9%): [2.166, 4.917] (assumes normal distribution)


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
# Warmup Iteration   1: 8.352 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.004 ms/op
Iteration   1: 3.349 ±(99.9%) 0.009 ms/op
Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
Iteration   3: 3.252 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.252, 3.294, 3.349), stdev = 0.050
  CI (99.9%): [2.380, 4.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.760 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.006 ms/op
Iteration   1: 3.571 ±(99.9%) 0.009 ms/op
Iteration   2: 3.467 ±(99.9%) 0.008 ms/op
Iteration   3: 3.418 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 1.426 ms/op [Average]
  (min, avg, max) = (3.418, 3.485, 3.571), stdev = 0.078
  CI (99.9%): [2.059, 4.911] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.863 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.007 ms/op
Iteration   1: 4.020 ±(99.9%) 0.009 ms/op
Iteration   2: 3.894 ±(99.9%) 0.016 ms/op
Iteration   3: 3.952 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.955 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.894, 3.955, 4.020), stdev = 0.063
  CI (99.9%): [2.802, 5.109] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.588 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.606 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.999 ms/op
                 createUser·p0.999:  21.616 ms/op
                 createUser·p0.9999: 24.045 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.630 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  25.428 ms/op
                 createUser·p0.9999: 28.482 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 3.526 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  21.403 ms/op
                 createUser·p0.9999: 28.511 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267617
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3608 
    [ 2.500,  5.000) = 255247 
    [ 5.000,  7.500) = 7271 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     28.319 ms/op
     p(99.9990) =     28.923 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 9.876 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.010 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.774 ms/op
                 existUser·p0.999:  23.006 ms/op
                 existUser·p0.9999: 29.636 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  22.920 ms/op
                 existUser·p0.9999: 27.115 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.297 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  21.836 ms/op
                 existUser·p0.9999: 38.207 ms/op
                 existUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285044
  mean =      3.364 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12512 
    [ 2.500,  5.000) = 266853 
    [ 5.000,  7.500) = 4659 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.796 ms/op
     p(99.9000) =     22.314 ms/op
     p(99.9900) =     37.650 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 11.966 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  20.948 ms/op
                 getUser·p0.9999: 25.041 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  22.730 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.552 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.200 ms/op
                 getUser·p0.999:  9.814 ms/op
                 getUser·p0.9999: 48.562 ms/op
                 getUser·p1.00:   49.545 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274777
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267463 
    [ 5.000, 10.000) = 6734 
    [10.000, 15.000) = 315 
    [15.000, 20.000) = 9 
    [20.000, 25.000) = 151 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     13.246 ms/op
     p(99.9900) =     46.727 ms/op
     p(99.9990) =     49.037 ms/op
     p(99.9999) =     49.545 ms/op
    p(100.0000) =     49.545 ms/op


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
# Warmup Iteration   1: 11.611 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.014 ms/op
Iteration   1: 4.201 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  24.084 ms/op
                 listUser·p0.9999: 31.077 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.795 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 18.498 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236016
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 223365 
    [ 5.000,  7.500) = 9944 
    [ 7.500, 10.000) = 1651 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     29.484 ms/op
     p(99.9990) =     31.401 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.018 ± 3.348  ops/ms
ClientPb.existUser                       thrpt       3   9.510 ± 3.071  ops/ms
ClientPb.getUser                         thrpt       3   9.372 ± 4.750  ops/ms
ClientPb.listUser                        thrpt       3   8.046 ± 2.159  ops/ms
ClientPb.createUser                       avgt       3   3.542 ± 1.375   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 0.914   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 1.426   ms/op
ClientPb.listUser                         avgt       3   3.955 ± 1.153   ms/op
ClientPb.createUser                     sample  267617   3.587 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.660           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.319           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.164           ms/op
ClientPb.existUser                      sample  285044   3.364 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.796           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.314           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.650           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  274777   3.492 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.246           ms/op
ClientPb.getUser:getUser·p0.9999        sample          46.727           ms/op
ClientPb.getUser:getUser·p1.00          sample          49.545           ms/op
ClientPb.listUser                       sample  236016   4.066 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.579           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
