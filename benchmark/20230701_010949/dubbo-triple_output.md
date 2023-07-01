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
# Warmup Iteration   1: 2.134 ops/ms
# Warmup Iteration   2: 5.755 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.206 ops/ms
Iteration   3: 9.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.242 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (9.066, 9.242, 9.455), stdev = 0.197
  CI (99.9%): [5.653, 12.832] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 8.952 ops/ms
# Warmup Iteration   3: 9.288 ops/ms
Iteration   1: 9.712 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.480 ±(99.9%) 7.094 ops/ms [Average]
  (min, avg, max) = (9.031, 9.480, 9.712), stdev = 0.389
  CI (99.9%): [2.386, 16.574] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 8.092 ops/ms
# Warmup Iteration   3: 9.057 ops/ms
Iteration   1: 8.905 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.090 ±(99.9%) 2.922 ops/ms [Average]
  (min, avg, max) = (8.905, 9.090, 9.188), stdev = 0.160
  CI (99.9%): [6.167, 12.012] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.321 ops/ms
# Warmup Iteration   3: 7.657 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 7.632 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.816 ±(99.9%) 4.616 ops/ms [Average]
  (min, avg, max) = (7.632, 7.816, 8.104), stdev = 0.253
  CI (99.9%): [3.199, 12.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.718 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.007 ms/op
Iteration   1: 3.382 ±(99.9%) 0.008 ms/op
Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
Iteration   3: 3.311 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.343 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.311, 3.343, 3.382), stdev = 0.036
  CI (99.9%): [2.680, 4.006] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.004 ms/op
Iteration   1: 3.324 ±(99.9%) 0.003 ms/op
Iteration   2: 3.282 ±(99.9%) 0.004 ms/op
Iteration   3: 3.152 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (3.152, 3.253, 3.324), stdev = 0.090
  CI (99.9%): [1.615, 4.891] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.577 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.007 ms/op
Iteration   1: 3.426 ±(99.9%) 0.003 ms/op
Iteration   2: 3.405 ±(99.9%) 0.008 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (3.405, 3.428, 3.453), stdev = 0.024
  CI (99.9%): [2.987, 3.869] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.996 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.013 ms/op
Iteration   1: 4.061 ±(99.9%) 0.007 ms/op
Iteration   2: 4.030 ±(99.9%) 0.009 ms/op
Iteration   3: 4.104 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.065 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (4.030, 4.065, 4.104), stdev = 0.037
  CI (99.9%): [3.390, 4.740] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.744 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.015 ms/op
Iteration   1: 3.608 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.420 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  23.921 ms/op
                 createUser·p0.9999: 28.578 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 3.596 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  21.637 ms/op
                 createUser·p0.9999: 28.523 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  22.234 ms/op
                 createUser·p0.9999: 28.765 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269007
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3989 
    [ 2.500,  5.000) = 258426 
    [ 5.000,  7.500) = 5258 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.037 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 9.379 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
Iteration   1: 3.332 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  21.807 ms/op
                 existUser·p0.9999: 31.064 ms/op
                 existUser·p1.00:   32.997 ms/op

Iteration   2: 3.286 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  13.938 ms/op
                 existUser·p0.9999: 27.635 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.445 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  19.090 ms/op
                 existUser·p0.9999: 27.278 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286208
  mean =      3.353 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15174 
    [ 2.500,  5.000) = 264645 
    [ 5.000,  7.500) = 5492 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     18.985 ms/op
     p(99.9900) =     29.078 ms/op
     p(99.9990) =     32.767 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 8.852 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
Iteration   1: 3.458 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 29.106 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   2: 3.508 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  8.499 ms/op
                 getUser·p0.9999: 29.880 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  21.027 ms/op
                 getUser·p0.9999: 30.935 ms/op
                 getUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276115
  mean =      3.477 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 267773 
    [ 5.000,  7.500) = 6850 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     30.192 ms/op
     p(99.9990) =     32.381 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 10.500 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.012 ms/op
Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  17.966 ms/op
                 listUser·p0.9999: 24.433 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.979 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.061 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.677 ms/op
                 listUser·p0.999:  14.800 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236621
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 228051 
    [ 5.000,  7.500) = 6073 
    [ 7.500, 10.000) = 1543 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     16.573 ms/op
     p(99.9900) =     23.538 ms/op
     p(99.9990) =     25.204 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.242 ± 3.589  ops/ms
ClientPb.existUser                       thrpt       3   9.480 ± 7.094  ops/ms
ClientPb.getUser                         thrpt       3   9.090 ± 2.922  ops/ms
ClientPb.listUser                        thrpt       3   7.816 ± 4.616  ops/ms
ClientPb.createUser                       avgt       3   3.343 ± 0.663   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 1.638   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 0.441   ms/op
ClientPb.listUser                         avgt       3   4.065 ± 0.675   ms/op
ClientPb.createUser                     sample  269007   3.567 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.278           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.605           ms/op
ClientPb.existUser                      sample  286208   3.353 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.985           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.078           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  276115   3.477 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.180           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.140           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.192           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.637           ms/op
ClientPb.listUser                       sample  236621   4.054 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.622           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.573           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.538           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
