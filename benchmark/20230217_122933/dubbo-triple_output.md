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
# Warmup Iteration   1: 2.730 ops/ms
# Warmup Iteration   2: 6.703 ops/ms
# Warmup Iteration   3: 9.454 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 9.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.840 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (9.744, 9.840, 9.952), stdev = 0.105
  CI (99.9%): [7.923, 11.756] (assumes normal distribution)


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
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 9.999 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.407 ±(99.9%) 3.131 ops/ms [Average]
  (min, avg, max) = (10.302, 10.407, 10.605), stdev = 0.172
  CI (99.9%): [7.276, 13.537] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 9.711 ops/ms
Iteration   1: 9.754 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.975 ±(99.9%) 3.787 ops/ms [Average]
  (min, avg, max) = (9.754, 9.975, 10.166), stdev = 0.208
  CI (99.9%): [6.189, 13.762] (assumes normal distribution)


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
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.483 ops/ms
Iteration   1: 8.809 ops/ms
Iteration   2: 8.638 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.688 ±(99.9%) 1.921 ops/ms [Average]
  (min, avg, max) = (8.617, 8.688, 8.809), stdev = 0.105
  CI (99.9%): [6.766, 10.609] (assumes normal distribution)


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
# Warmup Iteration   1: 7.816 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.006 ms/op
Iteration   3: 3.295 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 1.547 ms/op [Average]
  (min, avg, max) = (3.133, 3.229, 3.295), stdev = 0.085
  CI (99.9%): [1.682, 4.776] (assumes normal distribution)


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
# Warmup Iteration   1: 7.590 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 2.972 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (2.972, 3.055, 3.108), stdev = 0.073
  CI (99.9%): [1.731, 4.379] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.631 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.004 ms/op
Iteration   1: 3.290 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
Iteration   3: 3.273 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.138, 3.234, 3.290), stdev = 0.083
  CI (99.9%): [1.715, 4.753] (assumes normal distribution)


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
# Warmup Iteration   1: 8.693 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
Iteration   1: 3.717 ±(99.9%) 0.008 ms/op
Iteration   2: 3.619 ±(99.9%) 0.012 ms/op
Iteration   3: 3.734 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.690 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.619, 3.690, 3.734), stdev = 0.062
  CI (99.9%): [2.559, 4.822] (assumes normal distribution)


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
# Warmup Iteration   1: 7.960 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 22.904 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.763 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 28.592 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304728
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23551 
    [ 2.500,  5.000) = 275859 
    [ 5.000,  7.500) = 4460 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     16.152 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 7.610 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.799 ms/op
                 existUser·p0.9999: 17.468 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  10.529 ms/op
                 existUser·p0.9999: 19.807 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 21.384 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312749
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18782 
    [ 2.500,  5.000) = 290294 
    [ 5.000,  7.500) = 2965 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     10.555 ms/op
     p(99.9900) =     20.864 ms/op
     p(99.9990) =     22.376 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 7.859 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
Iteration   1: 3.157 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.466 ms/op
                 getUser·p0.999:  18.698 ms/op
                 getUser·p0.9999: 30.245 ms/op
                 getUser·p1.00:   32.637 ms/op

Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 22.679 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 21.228 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302024
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19696 
    [ 2.500,  5.000) = 277314 
    [ 5.000,  7.500) = 4337 
    [ 7.500, 10.000) = 240 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     17.102 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     32.636 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 11.241 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.013 ms/op
Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.555 ms/op
                 listUser·p0.999:  15.395 ms/op
                 listUser·p0.9999: 19.455 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 19.151 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.751 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253606
  mean =      3.784 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 243745 
    [ 5.000,  7.500) = 7967 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.342 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.870 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.840 ± 1.916  ops/ms
ClientPb.existUser                       thrpt       3  10.407 ± 3.131  ops/ms
ClientPb.getUser                         thrpt       3   9.975 ± 3.787  ops/ms
ClientPb.listUser                        thrpt       3   8.688 ± 1.921  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 1.547   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 1.324   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 1.519   ms/op
ClientPb.listUser                         avgt       3   3.690 ± 1.132   ms/op
ClientPb.createUser                     sample  304728   3.148 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.494           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.152           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.903           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.672           ms/op
ClientPb.existUser                      sample  312749   3.069 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.087           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.555           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.864           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.610           ms/op
ClientPb.getUser                        sample  302024   3.178 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.102           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.295           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.637           ms/op
ClientPb.listUser                       sample  253606   3.784 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.963           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.342           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.544           ms/op
