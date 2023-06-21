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
# Warmup Iteration   1: 2.037 ops/ms
# Warmup Iteration   2: 5.139 ops/ms
# Warmup Iteration   3: 8.283 ops/ms
Iteration   1: 8.892 ops/ms
Iteration   2: 9.245 ops/ms
Iteration   3: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.114 ±(99.9%) 3.525 ops/ms [Average]
  (min, avg, max) = (8.892, 9.114, 9.245), stdev = 0.193
  CI (99.9%): [5.590, 12.639] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.987 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 8.864 ops/ms
Iteration   1: 9.251 ops/ms
Iteration   2: 8.949 ops/ms
Iteration   3: 8.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.999 ±(99.9%) 4.225 ops/ms [Average]
  (min, avg, max) = (8.796, 8.999, 9.251), stdev = 0.232
  CI (99.9%): [4.773, 13.224] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 8.229 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.284 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.049 ±(99.9%) 5.569 ops/ms [Average]
  (min, avg, max) = (8.704, 9.049, 9.284), stdev = 0.305
  CI (99.9%): [3.480, 14.618] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 7.083 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.061 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.086 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (8.023, 8.086, 8.174), stdev = 0.078
  CI (99.9%): [6.654, 9.518] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.881 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.003 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
Iteration   2: 3.389 ±(99.9%) 0.008 ms/op
Iteration   3: 3.384 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.372, 3.382, 3.389), stdev = 0.009
  CI (99.9%): [3.222, 3.542] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.002 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.005 ms/op
Iteration   1: 3.149 ±(99.9%) 0.005 ms/op
Iteration   2: 3.367 ±(99.9%) 0.006 ms/op
Iteration   3: 3.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 2.108 ms/op [Average]
  (min, avg, max) = (3.149, 3.280, 3.367), stdev = 0.116
  CI (99.9%): [1.172, 5.388] (assumes normal distribution)


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
# Warmup Iteration   1: 11.468 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.007 ms/op
Iteration   1: 3.603 ±(99.9%) 0.003 ms/op
Iteration   2: 3.432 ±(99.9%) 0.007 ms/op
Iteration   3: 3.436 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.490 ±(99.9%) 1.781 ms/op [Average]
  (min, avg, max) = (3.432, 3.490, 3.603), stdev = 0.098
  CI (99.9%): [1.710, 5.271] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.129 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
Iteration   2: 4.006 ±(99.9%) 0.007 ms/op
Iteration   3: 3.944 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.960 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.931, 3.960, 4.006), stdev = 0.040
  CI (99.9%): [3.233, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 10.146 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.526 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  10.104 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  21.483 ms/op
                 createUser·p0.9999: 29.032 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   3: 3.420 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  23.939 ms/op
                 createUser·p0.9999: 28.530 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275734
  mean =      3.480 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6045 
    [ 2.500,  5.000) = 263759 
    [ 5.000,  7.500) = 5024 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     13.083 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     29.507 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.494 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.008 ms/op
Iteration   1: 3.415 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  20.796 ms/op
                 existUser·p0.9999: 23.697 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   6.313 ms/op
                 existUser·p0.999:  15.339 ms/op
                 existUser·p0.9999: 24.487 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  12.270 ms/op
                 existUser·p0.9999: 30.092 ms/op
                 existUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287466
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6424 
    [ 2.500,  5.000) = 275656 
    [ 5.000,  7.500) = 4371 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     19.174 ms/op
     p(99.9900) =     28.615 ms/op
     p(99.9990) =     30.720 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 8.699 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
Iteration   1: 3.509 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  20.562 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  22.541 ms/op
                 getUser·p0.9999: 31.706 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  17.793 ms/op
                 getUser·p0.9999: 24.078 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279216
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12287 
    [ 2.500,  5.000) = 260290 
    [ 5.000,  7.500) = 5400 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     18.228 ms/op
     p(99.9900) =     29.663 ms/op
     p(99.9990) =     31.899 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 11.096 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.016 ms/op
Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.122 ms/op
                 listUser·p0.999:  16.535 ms/op
                 listUser·p0.9999: 28.391 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 4.065 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 19.185 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.870 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.460 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242819
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 235530 
    [ 5.000,  7.500) = 5114 
    [ 7.500, 10.000) = 1506 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.114 ± 3.525  ops/ms
ClientPb.existUser                       thrpt       3   8.999 ± 4.225  ops/ms
ClientPb.getUser                         thrpt       3   9.049 ± 5.569  ops/ms
ClientPb.listUser                        thrpt       3   8.086 ± 1.432  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 0.160   ms/op
ClientPb.existUser                        avgt       3   3.280 ± 2.108   ms/op
ClientPb.getUser                          avgt       3   3.490 ± 1.781   ms/op
ClientPb.listUser                         avgt       3   3.960 ± 0.728   ms/op
ClientPb.createUser                     sample  275734   3.480 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.083           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  287466   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.064           ms/op
ClientPb.getUser                        sample  279216   3.437 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.228           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.663           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  242819   3.951 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.444           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
