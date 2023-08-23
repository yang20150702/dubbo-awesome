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
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 4.888 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 8.758 ops/ms
Iteration   2: 9.052 ops/ms
Iteration   3: 9.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.064 ±(99.9%) 5.700 ops/ms [Average]
  (min, avg, max) = (8.758, 9.064, 9.383), stdev = 0.312
  CI (99.9%): [3.364, 14.764] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.361 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.520 ±(99.9%) 3.551 ops/ms [Average]
  (min, avg, max) = (9.325, 9.520, 9.714), stdev = 0.195
  CI (99.9%): [5.970, 13.071] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.826 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 9.002 ops/ms
Iteration   2: 9.183 ops/ms
Iteration   3: 8.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.994 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (8.798, 8.994, 9.183), stdev = 0.192
  CI (99.9%): [5.482, 12.506] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.464 ops/ms
# Warmup Iteration   2: 7.046 ops/ms
# Warmup Iteration   3: 7.434 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.797 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (7.757, 7.797, 7.823), stdev = 0.035
  CI (99.9%): [7.155, 8.439] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.783 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.004 ms/op
Iteration   1: 3.603 ±(99.9%) 0.009 ms/op
Iteration   2: 3.662 ±(99.9%) 0.005 ms/op
Iteration   3: 3.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.611 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.568, 3.611, 3.662), stdev = 0.047
  CI (99.9%): [2.747, 4.476] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.487 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.007 ms/op
Iteration   1: 3.540 ±(99.9%) 0.007 ms/op
Iteration   2: 3.370 ±(99.9%) 0.003 ms/op
Iteration   3: 3.416 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.442 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.370, 3.442, 3.540), stdev = 0.088
  CI (99.9%): [1.831, 5.053] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 11.404 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.007 ms/op
Iteration   1: 3.647 ±(99.9%) 0.003 ms/op
Iteration   2: 3.509 ±(99.9%) 0.005 ms/op
Iteration   3: 3.586 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.581 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.509, 3.581, 3.647), stdev = 0.069
  CI (99.9%): [2.324, 4.837] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.824 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.010 ms/op
Iteration   1: 4.077 ±(99.9%) 0.009 ms/op
Iteration   2: 4.174 ±(99.9%) 0.011 ms/op
Iteration   3: 4.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.136 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (4.077, 4.136, 4.174), stdev = 0.052
  CI (99.9%): [3.190, 5.081] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.483 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.012 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 26.632 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 3.649 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.836 ms/op
                 createUser·p0.999:  24.074 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 3.567 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 29.735 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268625
  mean =      3.572 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3875 
    [ 2.500,  5.000) = 255845 
    [ 5.000,  7.500) = 7027 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     19.358 ms/op
     p(99.9900) =     29.037 ms/op
     p(99.9990) =     30.763 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.917 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
Iteration   1: 3.472 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  22.604 ms/op
                 existUser·p0.9999: 25.774 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.421 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  14.176 ms/op
                 existUser·p0.9999: 25.154 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.482 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  22.185 ms/op
                 existUser·p0.9999: 29.584 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277655
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8574 
    [ 2.500,  5.000) = 261407 
    [ 5.000,  7.500) = 5583 
    [ 7.500, 10.000) = 1243 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     27.155 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.787 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.012 ms/op
Iteration   1: 3.560 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  23.050 ms/op
                 getUser·p0.9999: 27.822 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  15.113 ms/op
                 getUser·p0.9999: 29.814 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   3: 3.474 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  24.454 ms/op
                 getUser·p0.9999: 29.399 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273510
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4059 
    [ 2.500,  5.000) = 259334 
    [ 5.000,  7.500) = 8375 
    [ 7.500, 10.000) = 1140 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.666 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.103 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.986 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.016 ms/op
Iteration   1: 4.190 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  22.730 ms/op
                 listUser·p0.9999: 25.047 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.179 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.572 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.623 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.150 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.911 ms/op
                 listUser·p0.999:  15.695 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229832
  mean =      4.173 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 218515 
    [ 5.000,  7.500) = 8216 
    [ 7.500, 10.000) = 1854 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     24.380 ms/op
     p(99.9990) =     25.652 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.064 ± 5.700  ops/ms
ClientPb.existUser                       thrpt       3   9.520 ± 3.551  ops/ms
ClientPb.getUser                         thrpt       3   8.994 ± 3.512  ops/ms
ClientPb.listUser                        thrpt       3   7.797 ± 0.642  ops/ms
ClientPb.createUser                       avgt       3   3.611 ± 0.864   ms/op
ClientPb.existUser                        avgt       3   3.442 ± 1.611   ms/op
ClientPb.getUser                          avgt       3   3.581 ± 1.257   ms/op
ClientPb.listUser                         avgt       3   4.136 ± 0.946   ms/op
ClientPb.createUser                     sample  268625   3.572 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.358           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.037           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  277655   3.458 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.531           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.155           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  273510   3.509 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.071           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.426           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  229832   4.173 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.186           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
