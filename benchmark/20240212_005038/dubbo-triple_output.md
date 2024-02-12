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
# Warmup Iteration   1: 5.199 ops/ms
# Warmup Iteration   2: 12.165 ops/ms
# Warmup Iteration   3: 12.365 ops/ms
Iteration   1: 12.523 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.615 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (12.523, 12.615, 12.711), stdev = 0.094
  CI (99.9%): [10.892, 14.338] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.483 ops/ms
# Warmup Iteration   2: 13.039 ops/ms
# Warmup Iteration   3: 13.104 ops/ms
Iteration   1: 12.918 ops/ms
Iteration   2: 13.021 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.914 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (12.803, 12.914, 13.021), stdev = 0.109
  CI (99.9%): [10.920, 14.908] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.132 ops/ms
# Warmup Iteration   2: 12.424 ops/ms
# Warmup Iteration   3: 12.682 ops/ms
Iteration   1: 12.815 ops/ms
Iteration   2: 12.832 ops/ms
Iteration   3: 12.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.855 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (12.815, 12.855, 12.918), stdev = 0.055
  CI (99.9%): [11.848, 13.862] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.380 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.617 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (10.579, 10.617, 10.669), stdev = 0.046
  CI (99.9%): [9.771, 11.464] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.542, 2.557, 2.565), stdev = 0.013
  CI (99.9%): [2.327, 2.787] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (2.426, 2.459, 2.481), stdev = 0.030
  CI (99.9%): [1.919, 2.999] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (2.475, 2.500, 2.529), stdev = 0.027
  CI (99.9%): [1.999, 3.000] (assumes normal distribution)


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.007 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.021 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (3.021, 3.024, 3.025), stdev = 0.003
  CI (99.9%): [2.977, 3.071] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  10.814 ms/op
                 createUser·p0.9999: 13.727 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  9.807 ms/op
                 createUser·p0.9999: 12.294 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 17.743 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380036
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181520 
    [ 2.500,  3.750) = 194666 
    [ 3.750,  5.000) = 2909 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      9.174 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     18.075 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.616 ms/op
                 existUser·p0.9999: 13.716 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.803 ms/op
                 existUser·p0.9999: 13.434 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.209 ms/op
                 existUser·p0.9999: 11.882 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389226
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 192966 
    [ 2.500,  3.750) = 192219 
    [ 3.750,  5.000) = 2914 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.170 ms/op
     p(99.9900) =     13.308 ms/op
     p(99.9990) =     14.294 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  6.198 ms/op
                 getUser·p0.9999: 13.222 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 12.659 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.940 ms/op
                 getUser·p0.9999: 11.079 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387274
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 193047 
    [ 2.500,  3.750) = 189473 
    [ 3.750,  5.000) = 3536 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      7.098 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     13.732 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.678 ms/op
                 listUser·p0.9999: 10.831 ms/op
                 listUser·p1.00:   11.076 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.056 ms/op
                 listUser·p0.9999: 11.344 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.651 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 12.536 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318848
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 92082 
    [ 2.500,  3.750) = 188523 
    [ 3.750,  5.000) = 30878 
    [ 5.000,  6.250) = 5971 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 265 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.096 ms/op
     p(99.9900) =     11.389 ms/op
     p(99.9990) =     12.760 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.615 ± 1.723  ops/ms
ClientPb.existUser                       thrpt       3  12.914 ± 1.994  ops/ms
ClientPb.getUser                         thrpt       3  12.855 ± 1.007  ops/ms
ClientPb.listUser                        thrpt       3  10.617 ± 0.846  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.230   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.540   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.501   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.047   ms/op
ClientPb.createUser                     sample  380036   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.964           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.219           ms/op
ClientPb.existUser                      sample  389226   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.783           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.170           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.308           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  387274   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.098           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.959           ms/op
ClientPb.listUser                       sample  318848   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.096           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
