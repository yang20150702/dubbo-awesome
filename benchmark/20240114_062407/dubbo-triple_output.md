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
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 12.186 ops/ms
# Warmup Iteration   3: 12.503 ops/ms
Iteration   1: 12.711 ops/ms
Iteration   2: 12.674 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.734 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (12.674, 12.734, 12.815), stdev = 0.073
  CI (99.9%): [11.401, 14.066] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.326 ops/ms
# Warmup Iteration   2: 13.306 ops/ms
# Warmup Iteration   3: 13.260 ops/ms
Iteration   1: 13.387 ops/ms
Iteration   2: 13.349 ops/ms
Iteration   3: 13.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.358 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (13.338, 13.358, 13.387), stdev = 0.026
  CI (99.9%): [12.888, 13.828] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.077 ops/ms
# Warmup Iteration   2: 12.684 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 13.019 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.926 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (12.869, 12.926, 13.019), stdev = 0.081
  CI (99.9%): [11.443, 14.408] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 10.782 ops/ms
Iteration   2: 10.857 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.810 ±(99.9%) 0.746 ops/ms [Average]
  (min, avg, max) = (10.782, 10.810, 10.857), stdev = 0.041
  CI (99.9%): [10.064, 11.556] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (2.485, 2.522, 2.558), stdev = 0.037
  CI (99.9%): [1.850, 3.194] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.424, 2.428, 2.435), stdev = 0.006
  CI (99.9%): [2.322, 2.534] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.441, 2.456, 2.479), stdev = 0.020
  CI (99.9%): [2.098, 2.815] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.004 ms/op
Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
Iteration   3: 3.008 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (3.001, 3.006, 3.009), stdev = 0.005
  CI (99.9%): [2.922, 3.090] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  11.364 ms/op
                 createUser·p0.9999: 13.754 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  7.773 ms/op
                 createUser·p0.9999: 12.599 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.622 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 20.551 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384604
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187429 
    [ 2.500,  5.000) = 196456 
    [ 5.000,  7.500) = 321 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     14.124 ms/op
     p(99.9990) =     21.140 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  5.806 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 10.450 ms/op
                 existUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396092
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 196019 
    [ 2.500,  3.750) = 196351 
    [ 3.750,  5.000) = 2492 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.551 ms/op
     p(99.9900) =     14.814 ms/op
     p(99.9990) =     17.409 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  6.261 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.789 ms/op
                 getUser·p0.9999: 12.051 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  5.398 ms/op
                 getUser·p0.9999: 11.552 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386643
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 192749 
    [ 2.500,  3.750) = 189537 
    [ 3.750,  5.000) = 3371 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.147 ms/op
     p(99.9900) =     13.473 ms/op
     p(99.9990) =     14.337 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.009 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  9.108 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 11.593 ms/op
                 listUser·p1.00:   13.910 ms/op

Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322494
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 100655 
    [ 2.500,  3.750) = 185048 
    [ 3.750,  5.000) = 30143 
    [ 5.000,  6.250) = 5336 
    [ 6.250,  7.500) = 519 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 282 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     12.184 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.734 ± 1.333  ops/ms
ClientPb.existUser                       thrpt       3  13.358 ± 0.470  ops/ms
ClientPb.getUser                         thrpt       3  12.926 ± 1.482  ops/ms
ClientPb.listUser                        thrpt       3  10.810 ± 0.746  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.672   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.106   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.359   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.084   ms/op
ClientPb.createUser                     sample  384604   2.494 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.877           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.398           ms/op
ClientPb.existUser                      sample  396092   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.352           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.814           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.662           ms/op
ClientPb.getUser                        sample  386643   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.751           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.147           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.473           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  322494   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.685           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.910           ms/op
