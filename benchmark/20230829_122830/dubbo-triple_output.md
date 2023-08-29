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
# Warmup Iteration   1: 1.072 ops/ms
# Warmup Iteration   2: 2.132 ops/ms
# Warmup Iteration   3: 4.786 ops/ms
Iteration   1: 5.632 ops/ms
Iteration   2: 5.621 ops/ms
Iteration   3: 5.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.740 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (5.621, 5.740, 5.967), stdev = 0.196
  CI (99.9%): [2.155, 9.325] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.540 ops/ms
# Warmup Iteration   2: 4.965 ops/ms
# Warmup Iteration   3: 6.134 ops/ms
Iteration   1: 6.426 ops/ms
Iteration   2: 6.426 ops/ms
Iteration   3: 6.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.444 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (6.426, 6.444, 6.479), stdev = 0.030
  CI (99.9%): [5.890, 6.998] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.498 ops/ms
# Warmup Iteration   2: 3.753 ops/ms
# Warmup Iteration   3: 5.377 ops/ms
Iteration   1: 5.630 ops/ms
Iteration   2: 5.880 ops/ms
Iteration   3: 5.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.821 ±(99.9%) 3.082 ops/ms [Average]
  (min, avg, max) = (5.630, 5.821, 5.952), stdev = 0.169
  CI (99.9%): [2.739, 8.902] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.562 ops/ms
# Warmup Iteration   2: 4.143 ops/ms
# Warmup Iteration   3: 4.862 ops/ms
Iteration   1: 4.707 ops/ms
Iteration   2: 5.085 ops/ms
Iteration   3: 4.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.915 ±(99.9%) 3.498 ops/ms [Average]
  (min, avg, max) = (4.707, 4.915, 5.085), stdev = 0.192
  CI (99.9%): [1.418, 8.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.950 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.034 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.621 ±(99.9%) 0.011 ms/op
Iteration   1: 5.460 ±(99.9%) 0.010 ms/op
Iteration   2: 5.678 ±(99.9%) 0.009 ms/op
Iteration   3: 5.487 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.541 ±(99.9%) 2.168 ms/op [Average]
  (min, avg, max) = (5.460, 5.541, 5.678), stdev = 0.119
  CI (99.9%): [3.373, 7.710] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.177 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.257 ±(99.9%) 0.008 ms/op
Iteration   1: 5.413 ±(99.9%) 0.007 ms/op
Iteration   2: 5.263 ±(99.9%) 0.011 ms/op
Iteration   3: 5.191 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.289 ±(99.9%) 2.060 ms/op [Average]
  (min, avg, max) = (5.191, 5.289, 5.413), stdev = 0.113
  CI (99.9%): [3.229, 7.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.333 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.305 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.564 ±(99.9%) 0.008 ms/op
Iteration   1: 5.372 ±(99.9%) 0.009 ms/op
Iteration   2: 5.718 ±(99.9%) 0.007 ms/op
Iteration   3: 5.441 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.510 ±(99.9%) 3.342 ms/op [Average]
  (min, avg, max) = (5.372, 5.510, 5.718), stdev = 0.183
  CI (99.9%): [2.169, 8.852] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.720 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 8.156 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.623 ±(99.9%) 0.007 ms/op
Iteration   1: 6.229 ±(99.9%) 0.014 ms/op
Iteration   2: 6.312 ±(99.9%) 0.017 ms/op
Iteration   3: 6.292 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.277 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (6.229, 6.277, 6.312), stdev = 0.043
  CI (99.9%): [5.485, 7.069] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.656 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 7.188 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.313 ±(99.9%) 0.034 ms/op
Iteration   1: 5.754 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.217 ms/op
                 createUser·p0.99:   11.633 ms/op
                 createUser·p0.999:  28.159 ms/op
                 createUser·p0.9999: 33.269 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   2: 5.792 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   11.600 ms/op
                 createUser·p0.999:  16.597 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 5.774 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.658 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.716 ms/op
                 createUser·p0.99:   11.993 ms/op
                 createUser·p0.999:  28.386 ms/op
                 createUser·p0.9999: 38.748 ms/op
                 createUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166205
  mean =      5.773 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 45542 
    [ 5.000,  7.500) = 106275 
    [ 7.500, 10.000) = 10756 
    [10.000, 12.500) = 2493 
    [12.500, 15.000) = 712 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     23.455 ms/op
     p(99.9900) =     36.856 ms/op
     p(99.9990) =     39.476 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.821 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.169 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.424 ±(99.9%) 0.020 ms/op
Iteration   1: 5.209 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.926 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  23.514 ms/op
                 existUser·p0.9999: 27.881 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 5.201 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.617 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  17.385 ms/op
                 existUser·p0.9999: 28.176 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   3: 5.218 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  14.117 ms/op
                 existUser·p0.9999: 34.791 ms/op
                 existUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184207
  mean =      5.210 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 107813 
    [ 5.000,  7.500) = 66027 
    [ 7.500, 10.000) = 8216 
    [10.000, 12.500) = 1503 
    [12.500, 15.000) = 411 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     18.245 ms/op
     p(99.9900) =     29.346 ms/op
     p(99.9990) =     35.562 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.587 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 6.117 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.023 ms/op
Iteration   1: 5.828 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.884 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   9.339 ms/op
                 getUser·p0.99:   13.156 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 29.106 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   2: 5.570 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.527 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.305 ms/op
                 getUser·p0.999:  16.171 ms/op
                 getUser·p0.9999: 32.696 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 5.665 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.613 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  28.918 ms/op
                 getUser·p0.9999: 32.255 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168763
  mean =      5.686 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 48077 
    [ 5.000,  7.500) = 108751 
    [ 7.500, 10.000) = 7989 
    [10.000, 12.500) = 2583 
    [12.500, 15.000) = 993 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.527 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     12.015 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     32.215 ms/op
     p(99.9990) =     33.575 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.833 ±(99.9%) 0.347 ms/op
# Warmup Iteration   2: 7.801 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.552 ±(99.9%) 0.026 ms/op
Iteration   1: 6.626 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.326 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   14.713 ms/op
                 listUser·p0.999:  27.777 ms/op
                 listUser·p0.9999: 32.004 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   2: 6.314 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.752 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  31.067 ms/op
                 listUser·p0.9999: 34.533 ms/op
                 listUser·p1.00:   38.797 ms/op

Iteration   3: 6.607 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.346 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.958 ms/op
                 listUser·p0.999:  25.008 ms/op
                 listUser·p0.9999: 31.659 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147306
  mean =      6.513 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 5396 
    [ 5.000,  7.500) = 124481 
    [ 7.500, 10.000) = 12181 
    [10.000, 12.500) = 3271 
    [12.500, 15.000) = 1110 
    [15.000, 17.500) = 356 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.384 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      7.758 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     13.271 ms/op
     p(99.9000) =     28.203 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     37.030 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.740 ± 3.585  ops/ms
ClientPb.existUser                       thrpt       3   6.444 ± 0.554  ops/ms
ClientPb.getUser                         thrpt       3   5.821 ± 3.082  ops/ms
ClientPb.listUser                        thrpt       3   4.915 ± 3.498  ops/ms
ClientPb.createUser                       avgt       3   5.541 ± 2.168   ms/op
ClientPb.existUser                        avgt       3   5.289 ± 2.060   ms/op
ClientPb.getUser                          avgt       3   5.510 ± 3.342   ms/op
ClientPb.listUser                         avgt       3   6.277 ± 0.792   ms/op
ClientPb.createUser                     sample  166205   5.773 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.363           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.698           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.455           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.856           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.649           ms/op
ClientPb.existUser                      sample  184207   5.210 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.318           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.717           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.240           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.245           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.346           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  168763   5.686 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.015           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.215           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  147306   6.513 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.271           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.797           ms/op
