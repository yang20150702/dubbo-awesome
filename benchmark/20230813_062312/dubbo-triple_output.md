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
# Warmup Iteration   1: 2.209 ops/ms
# Warmup Iteration   2: 5.885 ops/ms
# Warmup Iteration   3: 8.683 ops/ms
Iteration   1: 9.396 ops/ms
Iteration   2: 9.514 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.434 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (9.390, 9.434, 9.514), stdev = 0.070
  CI (99.9%): [8.153, 10.714] (assumes normal distribution)


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
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 8.749 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.883 ops/ms
Iteration   3: 9.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.818 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (9.719, 9.818, 9.883), stdev = 0.087
  CI (99.9%): [8.228, 11.407] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.711 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.152 ±(99.9%) 3.141 ops/ms [Average]
  (min, avg, max) = (9.006, 9.152, 9.342), stdev = 0.172
  CI (99.9%): [6.011, 12.293] (assumes normal distribution)


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
# Warmup Iteration   1: 2.750 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 7.896 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.891 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (7.835, 7.891, 7.941), stdev = 0.053
  CI (99.9%): [6.915, 8.866] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.856 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.004 ms/op
Iteration   1: 3.519 ±(99.9%) 0.010 ms/op
Iteration   2: 3.668 ±(99.9%) 0.005 ms/op
Iteration   3: 3.469 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.552 ±(99.9%) 1.888 ms/op [Average]
  (min, avg, max) = (3.469, 3.552, 3.668), stdev = 0.103
  CI (99.9%): [1.664, 5.440] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.003 ms/op
Iteration   2: 3.359 ±(99.9%) 0.005 ms/op
Iteration   3: 3.185 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.279 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (3.185, 3.279, 3.359), stdev = 0.088
  CI (99.9%): [1.676, 4.881] (assumes normal distribution)


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
# Warmup Iteration   1: 9.208 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.006 ms/op
Iteration   1: 3.441 ±(99.9%) 0.004 ms/op
Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
Iteration   3: 3.620 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.515 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (3.441, 3.515, 3.620), stdev = 0.094
  CI (99.9%): [1.807, 5.223] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.005 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.007 ms/op
Iteration   1: 4.128 ±(99.9%) 0.005 ms/op
Iteration   2: 4.025 ±(99.9%) 0.010 ms/op
Iteration   3: 4.064 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.072 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (4.025, 4.072, 4.128), stdev = 0.052
  CI (99.9%): [3.125, 5.020] (assumes normal distribution)


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
# Warmup Iteration   1: 9.775 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.690 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.857 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  19.813 ms/op
                 createUser·p0.9999: 22.391 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.792 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 29.023 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   3: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.424 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 25.045 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272058
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5464 
    [ 2.500,  5.000) = 257462 
    [ 5.000,  7.500) = 7605 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     28.495 ms/op
     p(99.9990) =     29.368 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 9.399 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
Iteration   1: 3.417 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.390 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.970 ms/op
                 existUser·p0.999:  21.202 ms/op
                 existUser·p0.9999: 25.582 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  18.832 ms/op
                 existUser·p0.9999: 26.004 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282303
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11036 
    [ 2.500,  5.000) = 263868 
    [ 5.000,  7.500) = 6023 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.127 ms/op
     p(99.9000) =     19.192 ms/op
     p(99.9900) =     25.471 ms/op
     p(99.9990) =     26.843 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 8.723 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.012 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.528 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  23.159 ms/op
                 getUser·p0.9999: 27.286 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 3.441 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  18.917 ms/op
                 getUser·p0.9999: 29.154 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276156
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3204 
    [ 2.500,  5.000) = 262931 
    [ 5.000,  7.500) = 8119 
    [ 7.500, 10.000) = 1357 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     28.160 ms/op
     p(99.9990) =     29.480 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 12.638 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.744 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.014 ms/op
Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  20.576 ms/op
                 listUser·p0.9999: 25.598 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.166 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236284
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 226195 
    [ 5.000,  7.500) = 7181 
    [ 7.500, 10.000) = 1759 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.387 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.434 ± 1.281  ops/ms
ClientPb.existUser                       thrpt       3   9.818 ± 1.590  ops/ms
ClientPb.getUser                         thrpt       3   9.152 ± 3.141  ops/ms
ClientPb.listUser                        thrpt       3   7.891 ± 0.976  ops/ms
ClientPb.createUser                       avgt       3   3.552 ± 1.888   ms/op
ClientPb.existUser                        avgt       3   3.279 ± 1.602   ms/op
ClientPb.getUser                          avgt       3   3.515 ± 1.708   ms/op
ClientPb.listUser                         avgt       3   4.072 ± 0.948   ms/op
ClientPb.createUser                     sample  272058   3.528 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.645           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  282303   3.399 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.323           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.127           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.471           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  276156   3.473 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.188           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.160           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  236284   4.063 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.936           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
