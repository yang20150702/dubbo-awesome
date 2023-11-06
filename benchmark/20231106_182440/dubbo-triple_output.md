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
# Warmup Iteration   1: 1.788 ops/ms
# Warmup Iteration   2: 5.103 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.917 ops/ms
Iteration   2: 9.055 ops/ms
Iteration   3: 8.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.967 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (8.917, 8.967, 9.055), stdev = 0.076
  CI (99.9%): [7.579, 10.356] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ops/ms
# Warmup Iteration   2: 8.583 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.483 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.469 ±(99.9%) 1.612 ops/ms [Average]
  (min, avg, max) = (9.374, 9.469, 9.549), stdev = 0.088
  CI (99.9%): [7.857, 11.081] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.597 ops/ms
# Warmup Iteration   2: 8.202 ops/ms
# Warmup Iteration   3: 9.070 ops/ms
Iteration   1: 9.209 ops/ms
Iteration   2: 8.921 ops/ms
Iteration   3: 9.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.138 ±(99.9%) 3.500 ops/ms [Average]
  (min, avg, max) = (8.921, 9.138, 9.284), stdev = 0.192
  CI (99.9%): [5.638, 12.638] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 6.993 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 7.779 ops/ms
Iteration   3: 7.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.681 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (7.539, 7.681, 7.779), stdev = 0.126
  CI (99.9%): [5.391, 9.971] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.383 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.003 ms/op
Iteration   1: 3.513 ±(99.9%) 0.004 ms/op
Iteration   2: 3.612 ±(99.9%) 0.002 ms/op
Iteration   3: 3.574 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.566 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.513, 3.566, 3.612), stdev = 0.050
  CI (99.9%): [2.658, 4.475] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.040 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.003 ms/op
Iteration   1: 3.386 ±(99.9%) 0.004 ms/op
Iteration   2: 3.401 ±(99.9%) 0.003 ms/op
Iteration   3: 3.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.417 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.386, 3.417, 3.464), stdev = 0.041
  CI (99.9%): [2.665, 4.169] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.369 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.004 ms/op
Iteration   1: 3.550 ±(99.9%) 0.003 ms/op
Iteration   2: 3.470 ±(99.9%) 0.006 ms/op
Iteration   3: 3.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.501 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.470, 3.501, 3.550), stdev = 0.043
  CI (99.9%): [2.725, 4.278] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.406 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.006 ms/op
Iteration   1: 4.091 ±(99.9%) 0.009 ms/op
Iteration   2: 4.139 ±(99.9%) 0.008 ms/op
Iteration   3: 4.149 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.126 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (4.091, 4.126, 4.149), stdev = 0.031
  CI (99.9%): [3.559, 4.694] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.842 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.010 ms/op
Iteration   1: 3.474 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.184 ms/op
                 createUser·p0.9999: 20.918 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.487 ms/op
                 createUser·p0.9999: 22.629 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.483 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  18.505 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278087
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6513 
    [ 2.500,  5.000) = 265629 
    [ 5.000,  7.500) = 4883 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     18.380 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.712 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.782 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
Iteration   1: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  17.815 ms/op
                 existUser·p0.9999: 22.294 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  21.685 ms/op
                 existUser·p0.9999: 24.231 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.328 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.892 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 31.765 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287899
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7204 
    [ 2.500,  5.000) = 274776 
    [ 5.000,  7.500) = 5006 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     18.976 ms/op
     p(99.9900) =     30.416 ms/op
     p(99.9990) =     33.087 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.293 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  15.451 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.509 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 20.640 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.985 ms/op
                 getUser·p0.999:  19.310 ms/op
                 getUser·p0.9999: 24.070 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273262
  mean =      3.512 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1912 
    [ 2.500,  5.000) = 263634 
    [ 5.000,  7.500) = 5679 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     22.108 ms/op
     p(99.9990) =     24.528 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 11.524 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.012 ms/op
Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  18.531 ms/op
                 listUser·p0.9999: 20.798 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 4.160 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.940 ms/op
                 listUser·p0.9999: 17.467 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 4.105 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.405 ms/op
                 listUser·p0.999:  15.325 ms/op
                 listUser·p0.9999: 17.322 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233209
  mean =      4.118 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 224579 
    [ 5.000,  7.500) = 6522 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.053 ms/op
     p(99.9900) =     19.683 ms/op
     p(99.9990) =     21.267 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.967 ± 1.388  ops/ms
ClientPb.existUser                       thrpt       3   9.469 ± 1.612  ops/ms
ClientPb.getUser                         thrpt       3   9.138 ± 3.500  ops/ms
ClientPb.listUser                        thrpt       3   7.681 ± 2.290  ops/ms
ClientPb.createUser                       avgt       3   3.566 ± 0.909   ms/op
ClientPb.existUser                        avgt       3   3.417 ± 0.752   ms/op
ClientPb.getUser                          avgt       3   3.501 ± 0.776   ms/op
ClientPb.listUser                         avgt       3   4.126 ± 0.568   ms/op
ClientPb.createUser                     sample  278087   3.449 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.380           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.854           ms/op
ClientPb.existUser                      sample  287899   3.334 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.416           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.325           ms/op
ClientPb.getUser                        sample  273262   3.512 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.108           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  233209   4.118 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.358           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.053           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.683           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.365           ms/op
