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
# Warmup Iteration   1: 2.060 ops/ms
# Warmup Iteration   2: 5.766 ops/ms
# Warmup Iteration   3: 8.710 ops/ms
Iteration   1: 9.422 ops/ms
Iteration   2: 8.872 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.188 ±(99.9%) 5.176 ops/ms [Average]
  (min, avg, max) = (8.872, 9.188, 9.422), stdev = 0.284
  CI (99.9%): [4.011, 14.364] (assumes normal distribution)


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
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.506 ops/ms
# Warmup Iteration   3: 9.350 ops/ms
Iteration   1: 9.864 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.852 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (9.720, 9.852, 9.973), stdev = 0.127
  CI (99.9%): [7.540, 12.165] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 9.001 ops/ms
Iteration   1: 9.727 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.522 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (9.380, 9.522, 9.727), stdev = 0.182
  CI (99.9%): [6.198, 12.846] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.936 ops/ms
# Warmup Iteration   2: 7.114 ops/ms
# Warmup Iteration   3: 7.779 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 7.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.037 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (7.992, 8.037, 8.115), stdev = 0.068
  CI (99.9%): [6.797, 9.278] (assumes normal distribution)


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
# Warmup Iteration   1: 9.605 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.005 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
Iteration   2: 3.410 ±(99.9%) 0.011 ms/op
Iteration   3: 3.408 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.408, 3.450, 3.531), stdev = 0.070
  CI (99.9%): [2.164, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 7.906 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.006 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
Iteration   2: 3.256 ±(99.9%) 0.011 ms/op
Iteration   3: 3.315 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.188, 3.253, 3.315), stdev = 0.063
  CI (99.9%): [2.098, 4.409] (assumes normal distribution)


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
# Warmup Iteration   1: 9.060 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.004 ms/op
Iteration   1: 3.451 ±(99.9%) 0.007 ms/op
Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
Iteration   3: 3.524 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.419, 3.465, 3.524), stdev = 0.054
  CI (99.9%): [2.487, 4.443] (assumes normal distribution)


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
# Warmup Iteration   1: 11.107 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
Iteration   1: 3.900 ±(99.9%) 0.014 ms/op
Iteration   2: 3.857 ±(99.9%) 0.013 ms/op
Iteration   3: 4.120 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 2.569 ms/op [Average]
  (min, avg, max) = (3.857, 3.959, 4.120), stdev = 0.141
  CI (99.9%): [1.390, 6.528] (assumes normal distribution)


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
# Warmup Iteration   1: 8.837 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
Iteration   1: 3.467 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.058 ms/op
                 createUser·p0.999:  21.910 ms/op
                 createUser·p0.9999: 29.189 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  21.715 ms/op
                 createUser·p0.9999: 32.031 ms/op
                 createUser·p1.00:   32.768 ms/op

Iteration   3: 3.241 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 24.155 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283395
  mean =      3.385 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7812 
    [ 2.500,  5.000) = 268770 
    [ 5.000,  7.500) = 5916 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     29.873 ms/op
     p(99.9990) =     32.653 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 9.072 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.220 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  15.156 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  10.054 ms/op
                 existUser·p0.9999: 23.546 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 25.331 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295942
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21586 
    [ 2.500,  5.000) = 268358 
    [ 5.000,  7.500) = 5078 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.099 ms/op
     p(99.9900) =     24.157 ms/op
     p(99.9990) =     26.203 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 9.273 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
Iteration   1: 3.384 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  17.382 ms/op
                 getUser·p0.9999: 20.137 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.344 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.596 ms/op
                 getUser·p0.999:  18.506 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.338 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  15.936 ms/op
                 getUser·p0.9999: 27.744 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286131
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 570 
    [ 2.500,  5.000) = 280442 
    [ 5.000,  7.500) = 4216 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     17.297 ms/op
     p(99.9900) =     26.010 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 11.049 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 23.440 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.943 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 18.838 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.814 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 15.673 ms/op
                 listUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245711
  mean =      3.904 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 239497 
    [ 5.000,  7.500) = 4467 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.881 ms/op
     p(99.9900) =     21.950 ms/op
     p(99.9990) =     26.419 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.188 ± 5.176  ops/ms
ClientPb.existUser                       thrpt       3   9.852 ± 2.312  ops/ms
ClientPb.getUser                         thrpt       3   9.522 ± 3.324  ops/ms
ClientPb.listUser                        thrpt       3   8.037 ± 1.241  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 1.285   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 1.156   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 0.978   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 2.569   ms/op
ClientPb.createUser                     sample  283395   3.385 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.401           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  295942   3.245 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.099           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.157           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  286131   3.355 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.536           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.297           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.010           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.770           ms/op
ClientPb.listUser                       sample  245711   3.904 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.620           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.881           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.950           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
