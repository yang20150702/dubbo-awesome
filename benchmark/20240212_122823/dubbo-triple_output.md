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
# Warmup Iteration   1: 5.303 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.466 ops/ms
Iteration   1: 12.541 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.702 ±(99.9%) 2.816 ops/ms [Average]
  (min, avg, max) = (12.541, 12.702, 12.849), stdev = 0.154
  CI (99.9%): [9.886, 15.518] (assumes normal distribution)


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
# Warmup Iteration   1: 8.355 ops/ms
# Warmup Iteration   2: 13.088 ops/ms
# Warmup Iteration   3: 13.072 ops/ms
Iteration   1: 13.127 ops/ms
Iteration   2: 13.193 ops/ms
Iteration   3: 13.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.141 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (13.103, 13.141, 13.193), stdev = 0.046
  CI (99.9%): [12.293, 13.988] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.837 ops/ms
# Warmup Iteration   2: 12.799 ops/ms
# Warmup Iteration   3: 12.998 ops/ms
Iteration   1: 13.253 ops/ms
Iteration   2: 13.222 ops/ms
Iteration   3: 13.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.198 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (13.120, 13.198, 13.253), stdev = 0.070
  CI (99.9%): [11.930, 14.466] (assumes normal distribution)


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
# Warmup Iteration   1: 6.701 ops/ms
# Warmup Iteration   2: 10.722 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 10.907 ops/ms
Iteration   3: 10.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.881 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (10.847, 10.881, 10.907), stdev = 0.030
  CI (99.9%): [10.326, 11.435] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.537, 2.542, 2.546), stdev = 0.005
  CI (99.9%): [2.456, 2.627] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.396 ±(99.9%) 0.004 ms/op
Iteration   1: 2.397 ±(99.9%) 0.004 ms/op
Iteration   2: 2.397 ±(99.9%) 0.002 ms/op
Iteration   3: 2.407 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.397, 2.400, 2.407), stdev = 0.006
  CI (99.9%): [2.297, 2.503] (assumes normal distribution)


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.003 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.438 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.433, 2.438, 2.440), stdev = 0.004
  CI (99.9%): [2.363, 2.512] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.577 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.004 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.956, 2.964, 2.979), stdev = 0.013
  CI (99.9%): [2.731, 3.198] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  7.954 ms/op
                 createUser·p0.9999: 13.437 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.464 ms/op
                 createUser·p0.9999: 12.095 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.927 ms/op
                 createUser·p0.999:  8.358 ms/op
                 createUser·p0.9999: 10.813 ms/op
                 createUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384555
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 187312 
    [ 2.500,  3.750) = 193552 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.338 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  6.970 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  7.475 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  9.010 ms/op
                 existUser·p0.9999: 11.633 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398077
  mean =      2.410 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 201283 
    [ 2.500,  3.750) = 193114 
    [ 3.750,  5.000) = 2711 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.215 ms/op
     p(99.9900) =     13.113 ms/op
     p(99.9990) =     14.452 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.929 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 13.980 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.184 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  9.714 ms/op
                 getUser·p0.9999: 14.279 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  8.240 ms/op
                 getUser·p0.9999: 11.661 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386457
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 193050 
    [ 2.500,  3.750) = 188948 
    [ 3.750,  5.000) = 3517 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      6.640 ms/op
     p(99.9900) =     13.873 ms/op
     p(99.9990) =     14.731 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.620 ms/op
                 listUser·p1.00:   13.763 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.401 ms/op
                 listUser·p0.9999: 10.767 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  9.259 ms/op
                 listUser·p0.9999: 11.151 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323564
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 99634 
    [ 2.500,  3.750) = 187231 
    [ 3.750,  5.000) = 30383 
    [ 5.000,  6.250) = 4972 
    [ 6.250,  7.500) = 508 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 325 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.259 ms/op
     p(99.9990) =     13.240 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.702 ± 2.816  ops/ms
ClientPb.existUser                       thrpt       3  13.141 ± 0.847  ops/ms
ClientPb.getUser                         thrpt       3  13.198 ± 1.268  ops/ms
ClientPb.listUser                        thrpt       3  10.881 ± 0.554  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.086   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.103   ms/op
ClientPb.getUser                          avgt       3   2.438 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.233   ms/op
ClientPb.createUser                     sample  384555   2.494 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.628           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.338           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.352           ms/op
ClientPb.existUser                      sample  398077   2.410 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.791           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.215           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.113           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  386457   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.640           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.873           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  323564   2.965 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.768           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.259           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.763           ms/op
