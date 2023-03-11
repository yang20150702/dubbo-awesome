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
# Warmup Iteration   1: 2.529 ops/ms
# Warmup Iteration   2: 6.248 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.760 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (9.652, 9.760, 9.832), stdev = 0.096
  CI (99.9%): [8.015, 11.506] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 9.348 ops/ms
# Warmup Iteration   3: 9.660 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.409 ±(99.9%) 6.258 ops/ms [Average]
  (min, avg, max) = (10.183, 10.409, 10.803), stdev = 0.343
  CI (99.9%): [4.151, 16.666] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ops/ms
# Warmup Iteration   2: 9.434 ops/ms
# Warmup Iteration   3: 10.185 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 9.826 ops/ms
Iteration   3: 9.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.689 ±(99.9%) 2.265 ops/ms [Average]
  (min, avg, max) = (9.585, 9.689, 9.826), stdev = 0.124
  CI (99.9%): [7.424, 11.954] (assumes normal distribution)


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
# Warmup Iteration   1: 3.151 ops/ms
# Warmup Iteration   2: 7.445 ops/ms
# Warmup Iteration   3: 8.598 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.457 ops/ms
Iteration   3: 8.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.514 ±(99.9%) 4.063 ops/ms [Average]
  (min, avg, max) = (8.326, 8.514, 8.760), stdev = 0.223
  CI (99.9%): [4.451, 12.578] (assumes normal distribution)


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
# Warmup Iteration   1: 7.844 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.006 ms/op
Iteration   1: 3.284 ±(99.9%) 0.003 ms/op
Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
Iteration   3: 3.089 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.152 ±(99.9%) 2.087 ms/op [Average]
  (min, avg, max) = (3.083, 3.152, 3.284), stdev = 0.114
  CI (99.9%): [1.065, 5.239] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.952 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
Iteration   1: 3.189 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.060 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.095 ±(99.9%) 1.513 ms/op [Average]
  (min, avg, max) = (3.035, 3.095, 3.189), stdev = 0.083
  CI (99.9%): [1.582, 4.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.568 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.002 ms/op
Iteration   1: 3.185 ±(99.9%) 0.007 ms/op
Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
Iteration   3: 3.289 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.715 ms/op [Average]
  (min, avg, max) = (3.101, 3.192, 3.289), stdev = 0.094
  CI (99.9%): [1.477, 4.906] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.110 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.008 ms/op
Iteration   1: 3.757 ±(99.9%) 0.004 ms/op
Iteration   2: 3.681 ±(99.9%) 0.006 ms/op
Iteration   3: 3.649 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.649, 3.696, 3.757), stdev = 0.056
  CI (99.9%): [2.679, 4.712] (assumes normal distribution)


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
# Warmup Iteration   1: 7.123 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.926 ms/op
                 createUser·p0.999:  12.397 ms/op
                 createUser·p0.9999: 23.796 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.197 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.269 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.827 ms/op
                 createUser·p0.9999: 35.520 ms/op
                 createUser·p1.00:   35.848 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  17.575 ms/op
                 createUser·p0.9999: 22.457 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301131
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16610 
    [ 2.500,  5.000) = 278160 
    [ 5.000,  7.500) = 5352 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     17.461 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     35.782 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.338 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 20.952 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.667 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  10.526 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.236 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 29.386 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306027
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27262 
    [ 2.500,  5.000) = 274080 
    [ 5.000,  7.500) = 3919 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.236 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     26.122 ms/op
     p(99.9990) =     30.276 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   6.309 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 20.573 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.125 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.483 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 19.591 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306197
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9220 
    [ 2.500,  5.000) = 292162 
    [ 5.000,  7.500) = 3943 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.250 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 9.263 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.012 ms/op
Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 26.822 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 14.639 ms/op
                 listUser·p1.00:   14.647 ms/op

Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 17.263 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252548
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 243482 
    [ 5.000,  7.500) = 7215 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.819 ms/op
     p(99.9900) =     25.092 ms/op
     p(99.9990) =     30.492 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.760 ± 1.746  ops/ms
ClientPb.existUser                       thrpt       3  10.409 ± 6.258  ops/ms
ClientPb.getUser                         thrpt       3   9.689 ± 2.265  ops/ms
ClientPb.listUser                        thrpt       3   8.514 ± 4.063  ops/ms
ClientPb.createUser                       avgt       3   3.152 ± 2.087   ms/op
ClientPb.existUser                        avgt       3   3.095 ± 1.513   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.715   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 1.016   ms/op
ClientPb.createUser                     sample  301131   3.188 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.269           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.461           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.620           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  306027   3.136 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.236           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.122           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  306197   3.131 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.250           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.660           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.134           ms/op
ClientPb.listUser                       sample  252548   3.801 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.819           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.092           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.261           ms/op
