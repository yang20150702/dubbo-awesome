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
# Warmup Iteration   1: 4.697 ops/ms
# Warmup Iteration   2: 12.156 ops/ms
# Warmup Iteration   3: 12.572 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 13.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.939 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (12.804, 12.939, 13.028), stdev = 0.118
  CI (99.9%): [10.777, 15.101] (assumes normal distribution)


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
# Warmup Iteration   1: 8.382 ops/ms
# Warmup Iteration   2: 13.438 ops/ms
# Warmup Iteration   3: 13.251 ops/ms
Iteration   1: 13.473 ops/ms
Iteration   2: 13.401 ops/ms
Iteration   3: 13.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.413 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (13.366, 13.413, 13.473), stdev = 0.055
  CI (99.9%): [12.418, 14.409] (assumes normal distribution)


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
# Warmup Iteration   1: 8.278 ops/ms
# Warmup Iteration   2: 12.917 ops/ms
# Warmup Iteration   3: 12.987 ops/ms
Iteration   1: 13.258 ops/ms
Iteration   2: 13.138 ops/ms
Iteration   3: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.167 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (13.106, 13.167, 13.258), stdev = 0.080
  CI (99.9%): [11.704, 14.631] (assumes normal distribution)


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
# Warmup Iteration   1: 7.003 ops/ms
# Warmup Iteration   2: 10.478 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.805 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.768 ±(99.9%) 1.133 ops/ms [Average]
  (min, avg, max) = (10.696, 10.768, 10.805), stdev = 0.062
  CI (99.9%): [9.635, 11.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.003 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (2.449, 2.471, 2.501), stdev = 0.027
  CI (99.9%): [1.976, 2.965] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.553 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.380 ±(99.9%) 0.004 ms/op
Iteration   1: 2.397 ±(99.9%) 0.004 ms/op
Iteration   2: 2.382 ±(99.9%) 0.004 ms/op
Iteration   3: 2.376 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.385 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.376, 2.385, 2.397), stdev = 0.011
  CI (99.9%): [2.193, 2.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.004 ms/op
Iteration   1: 2.413 ±(99.9%) 0.003 ms/op
Iteration   2: 2.411 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.405 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.389, 2.405, 2.413), stdev = 0.013
  CI (99.9%): [2.162, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
Iteration   1: 2.931 ±(99.9%) 0.007 ms/op
Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
Iteration   3: 2.913 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.917 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.908, 2.917, 2.931), stdev = 0.012
  CI (99.9%): [2.704, 3.131] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.857 ms/op
                 createUser·p0.999:  8.732 ms/op
                 createUser·p0.9999: 14.322 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   3.514 ms/op
                 createUser·p0.999:  6.824 ms/op
                 createUser·p0.9999: 11.485 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.038 ms/op
                 createUser·p0.9999: 11.010 ms/op
                 createUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389533
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 190782 
    [ 2.500,  3.750) = 195052 
    [ 3.750,  5.000) = 2899 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      6.820 ms/op
     p(99.9900) =     12.666 ms/op
     p(99.9990) =     15.108 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.383 ±(99.9%) 0.005 ms/op
Iteration   1: 2.373 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  4.907 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 12.920 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  9.042 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402332
  mean =      2.384 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 207025 
    [ 2.500,  3.750) = 192588 
    [ 3.750,  5.000) = 2001 
    [ 5.000,  6.250) = 161 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      7.572 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     14.079 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.006 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.502 ms/op
                 getUser·p0.999:  6.147 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.167 ms/op
                 getUser·p0.99:   3.964 ms/op
                 getUser·p0.999:  7.996 ms/op
                 getUser·p0.9999: 11.966 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  6.241 ms/op
                 getUser·p0.9999: 11.796 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392107
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 199218 
    [ 2.500,  3.750) = 189294 
    [ 3.750,  5.000) = 2711 
    [ 5.000,  6.250) = 323 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      7.537 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.158 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
Iteration   1: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.648 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 10.551 ms/op
                 listUser·p1.00:   11.026 ms/op

Iteration   2: 2.922 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.684 ms/op
                 listUser·p0.9999: 10.930 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 2.927 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  8.370 ms/op
                 listUser·p0.9999: 10.454 ms/op
                 listUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327080
  mean =      2.932 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 106441 
    [ 2.500,  3.750) = 185570 
    [ 3.750,  5.000) = 29012 
    [ 5.000,  6.250) = 4681 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 198 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     10.774 ms/op
     p(99.9990) =     12.011 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.939 ± 2.162  ops/ms
ClientPb.existUser                       thrpt       3  13.413 ± 0.996  ops/ms
ClientPb.getUser                         thrpt       3  13.167 ± 1.464  ops/ms
ClientPb.listUser                        thrpt       3  10.768 ± 1.133  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.495   ms/op
ClientPb.existUser                        avgt       3   2.385 ± 0.192   ms/op
ClientPb.getUser                          avgt       3   2.405 ± 0.243   ms/op
ClientPb.listUser                         avgt       3   2.917 ± 0.214   ms/op
ClientPb.createUser                     sample  389533   2.462 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.799           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.820           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.666           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  402332   2.384 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.572           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  392107   2.446 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.537           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  327080   2.932 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.648           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.774           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
