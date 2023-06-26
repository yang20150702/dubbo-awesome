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
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 4.966 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 9.401 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.316 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (9.208, 9.316, 9.401), stdev = 0.098
  CI (99.9%): [7.520, 11.111] (assumes normal distribution)


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
# Warmup Iteration   1: 3.060 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.740 ops/ms
Iteration   1: 9.719 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.724 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (9.664, 9.724, 9.788), stdev = 0.062
  CI (99.9%): [8.595, 10.853] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 8.666 ops/ms
# Warmup Iteration   3: 9.345 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.392 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.386 ±(99.9%) 4.460 ops/ms [Average]
  (min, avg, max) = (9.139, 9.386, 9.628), stdev = 0.244
  CI (99.9%): [4.926, 13.846] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 7.151 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.022 ±(99.9%) 3.246 ops/ms [Average]
  (min, avg, max) = (7.821, 8.022, 8.158), stdev = 0.178
  CI (99.9%): [4.776, 11.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.496 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.007 ms/op
Iteration   1: 3.438 ±(99.9%) 0.010 ms/op
Iteration   2: 3.346 ±(99.9%) 0.006 ms/op
Iteration   3: 3.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.401 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.346, 3.401, 3.438), stdev = 0.048
  CI (99.9%): [2.519, 4.284] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.692 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.006 ms/op
Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
Iteration   3: 3.286 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.265, 3.298, 3.342), stdev = 0.040
  CI (99.9%): [2.572, 4.024] (assumes normal distribution)


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
# Warmup Iteration   1: 9.263 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.005 ms/op
Iteration   1: 3.521 ±(99.9%) 0.005 ms/op
Iteration   2: 3.385 ±(99.9%) 0.007 ms/op
Iteration   3: 3.481 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.462 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (3.385, 3.462, 3.521), stdev = 0.070
  CI (99.9%): [2.186, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 10.681 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.008 ms/op
Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
Iteration   3: 3.956 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (3.952, 3.956, 3.960), stdev = 0.004
  CI (99.9%): [3.883, 4.029] (assumes normal distribution)


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
# Warmup Iteration   1: 9.858 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.011 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 3.341 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  24.167 ms/op
                 createUser·p0.9999: 40.108 ms/op
                 createUser·p1.00:   40.632 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  17.662 ms/op
                 createUser·p0.9999: 25.167 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282218
  mean =      3.401 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 276826 
    [ 5.000, 10.000) = 5037 
    [10.000, 15.000) = 67 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 83 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     17.753 ms/op
     p(99.9900) =     39.030 ms/op
     p(99.9990) =     40.525 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 8.812 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.008 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  19.711 ms/op
                 existUser·p0.9999: 23.351 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  22.945 ms/op
                 existUser·p0.9999: 25.989 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.383 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  20.725 ms/op
                 existUser·p0.9999: 33.409 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282961
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10386 
    [ 2.500,  5.000) = 267199 
    [ 5.000,  7.500) = 4703 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     32.431 ms/op
     p(99.9990) =     34.286 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 8.961 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  13.189 ms/op
                 getUser·p0.9999: 23.440 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 27.091 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.406 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  24.384 ms/op
                 getUser·p0.9999: 33.594 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279400
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7683 
    [ 2.500,  5.000) = 264292 
    [ 5.000,  7.500) = 6411 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     13.215 ms/op
     p(99.9900) =     30.738 ms/op
     p(99.9990) =     34.316 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 10.938 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.013 ms/op
Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   7.993 ms/op
                 listUser·p0.999:  21.475 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.908 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  15.569 ms/op
                 listUser·p0.9999: 18.077 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.895 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.284 ms/op
                 listUser·p0.9999: 17.229 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242407
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 232906 
    [ 5.000,  7.500) = 6863 
    [ 7.500, 10.000) = 1653 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     23.118 ms/op
     p(99.9990) =     24.277 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.316 ± 1.795  ops/ms
ClientPb.existUser                       thrpt       3   9.724 ± 1.129  ops/ms
ClientPb.getUser                         thrpt       3   9.386 ± 4.460  ops/ms
ClientPb.listUser                        thrpt       3   8.022 ± 3.246  ops/ms
ClientPb.createUser                       avgt       3   3.401 ± 0.882   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 0.726   ms/op
ClientPb.getUser                          avgt       3   3.462 ± 1.277   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 0.073   ms/op
ClientPb.createUser                     sample  282218   3.401 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.753           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.030           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  282961   3.391 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.174           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.825           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  279400   3.434 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.738           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  242407   3.955 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.118           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
