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
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.903 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.167 ±(99.9%) 5.239 ops/ms [Average]
  (min, avg, max) = (8.903, 9.167, 9.472), stdev = 0.287
  CI (99.9%): [3.928, 14.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.521 ops/ms
# Warmup Iteration   2: 7.937 ops/ms
# Warmup Iteration   3: 9.437 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.508 ops/ms
Iteration   3: 9.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.629 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (9.508, 9.629, 9.750), stdev = 0.121
  CI (99.9%): [7.424, 11.835] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.156 ops/ms
# Warmup Iteration   2: 8.260 ops/ms
# Warmup Iteration   3: 9.092 ops/ms
Iteration   1: 9.042 ops/ms
Iteration   2: 8.848 ops/ms
Iteration   3: 8.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.949 ±(99.9%) 1.771 ops/ms [Average]
  (min, avg, max) = (8.848, 8.949, 9.042), stdev = 0.097
  CI (99.9%): [7.177, 10.720] (assumes normal distribution)


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
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 7.267 ops/ms
# Warmup Iteration   3: 8.100 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.035 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (7.976, 8.035, 8.080), stdev = 0.053
  CI (99.9%): [7.064, 9.005] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.302 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.005 ms/op
Iteration   1: 3.488 ±(99.9%) 0.004 ms/op
Iteration   2: 3.470 ±(99.9%) 0.008 ms/op
Iteration   3: 3.418 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.418, 3.459, 3.488), stdev = 0.037
  CI (99.9%): [2.791, 4.126] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.771 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.007 ms/op
Iteration   1: 3.513 ±(99.9%) 0.004 ms/op
Iteration   2: 3.312 ±(99.9%) 0.003 ms/op
Iteration   3: 3.271 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.365 ±(99.9%) 2.366 ms/op [Average]
  (min, avg, max) = (3.271, 3.365, 3.513), stdev = 0.130
  CI (99.9%): [0.999, 5.731] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.673 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.003 ms/op
Iteration   1: 3.402 ±(99.9%) 0.006 ms/op
Iteration   2: 3.538 ±(99.9%) 0.006 ms/op
Iteration   3: 3.430 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.402, 3.456, 3.538), stdev = 0.072
  CI (99.9%): [2.151, 4.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.359 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.009 ms/op
Iteration   1: 4.071 ±(99.9%) 0.009 ms/op
Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
Iteration   3: 4.071 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.065 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (4.053, 4.065, 4.071), stdev = 0.010
  CI (99.9%): [3.879, 4.251] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.187 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 23.946 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  21.413 ms/op
                 createUser·p0.9999: 25.251 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.617 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  18.710 ms/op
                 createUser·p0.9999: 25.819 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273708
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3828 
    [ 2.500,  5.000) = 263640 
    [ 5.000,  7.500) = 5185 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     19.605 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.487 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  21.396 ms/op
                 existUser·p0.9999: 28.049 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.033 ms/op
                 existUser·p0.999:  21.730 ms/op
                 existUser·p0.9999: 25.156 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  21.561 ms/op
                 existUser·p0.9999: 28.708 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279375
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16824 
    [ 2.500,  5.000) = 255096 
    [ 5.000,  7.500) = 6290 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     27.922 ms/op
     p(99.9990) =     30.920 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.639 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.010 ms/op
Iteration   1: 3.445 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 22.614 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.435 ms/op
                 getUser·p0.999:  22.304 ms/op
                 getUser·p0.9999: 25.382 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  22.839 ms/op
                 getUser·p0.9999: 27.951 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277690
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6071 
    [ 2.500,  5.000) = 263847 
    [ 5.000,  7.500) = 6607 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.243 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     26.598 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.687 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.014 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  21.062 ms/op
                 listUser·p0.9999: 23.657 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.012 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   16.171 ms/op

Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 19.398 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240286
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 231939 
    [ 5.000,  7.500) = 6111 
    [ 7.500, 10.000) = 1446 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     22.838 ms/op
     p(99.9990) =     24.405 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.167 ± 5.239  ops/ms
ClientPb.existUser                       thrpt       3   9.629 ± 2.206  ops/ms
ClientPb.getUser                         thrpt       3   8.949 ± 1.771  ops/ms
ClientPb.listUser                        thrpt       3   8.035 ± 0.970  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.668   ms/op
ClientPb.existUser                        avgt       3   3.365 ± 2.366   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 1.305   ms/op
ClientPb.listUser                         avgt       3   4.065 ± 0.186   ms/op
ClientPb.createUser                     sample  273708   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.605           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  279375   3.433 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.766           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  277690   3.457 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.554           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.243           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  240286   3.995 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.097           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.838           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
