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
# Warmup Iteration   1: 1.906 ops/ms
# Warmup Iteration   2: 5.135 ops/ms
# Warmup Iteration   3: 8.241 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 8.978 ops/ms
Iteration   3: 9.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.092 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (8.978, 9.092, 9.158), stdev = 0.099
  CI (99.9%): [7.292, 10.892] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 9.531 ops/ms
Iteration   1: 9.566 ops/ms
Iteration   2: 9.619 ops/ms
Iteration   3: 9.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.512 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (9.351, 9.512, 9.619), stdev = 0.142
  CI (99.9%): [6.925, 12.100] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.533 ops/ms
# Warmup Iteration   2: 8.361 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 8.779 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.099 ±(99.9%) 5.276 ops/ms [Average]
  (min, avg, max) = (8.779, 9.099, 9.341), stdev = 0.289
  CI (99.9%): [3.823, 14.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.338 ops/ms
# Warmup Iteration   3: 7.523 ops/ms
Iteration   1: 7.414 ops/ms
Iteration   2: 7.483 ops/ms
Iteration   3: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.460 ±(99.9%) 0.735 ops/ms [Average]
  (min, avg, max) = (7.414, 7.460, 7.484), stdev = 0.040
  CI (99.9%): [6.726, 8.195] (assumes normal distribution)


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
# Warmup Iteration   1: 10.860 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.004 ms/op
Iteration   1: 3.513 ±(99.9%) 0.005 ms/op
Iteration   2: 3.637 ±(99.9%) 0.005 ms/op
Iteration   3: 3.785 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.645 ±(99.9%) 2.488 ms/op [Average]
  (min, avg, max) = (3.513, 3.645, 3.785), stdev = 0.136
  CI (99.9%): [1.157, 6.132] (assumes normal distribution)


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
# Warmup Iteration   1: 9.811 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.003 ms/op
Iteration   1: 3.369 ±(99.9%) 0.004 ms/op
Iteration   2: 3.470 ±(99.9%) 0.005 ms/op
Iteration   3: 3.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.423 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.369, 3.423, 3.470), stdev = 0.051
  CI (99.9%): [2.501, 4.344] (assumes normal distribution)


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
# Warmup Iteration   1: 10.871 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.005 ms/op
Iteration   1: 3.482 ±(99.9%) 0.004 ms/op
Iteration   2: 3.479 ±(99.9%) 0.004 ms/op
Iteration   3: 3.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.478 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (3.471, 3.478, 3.482), stdev = 0.006
  CI (99.9%): [3.374, 3.581] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.968 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.008 ms/op
Iteration   1: 4.253 ±(99.9%) 0.006 ms/op
Iteration   2: 4.143 ±(99.9%) 0.006 ms/op
Iteration   3: 4.117 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.171 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (4.117, 4.171, 4.253), stdev = 0.072
  CI (99.9%): [2.857, 5.485] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.168 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
Iteration   1: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  20.494 ms/op
                 createUser·p0.9999: 31.675 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   2: 3.541 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.736 ms/op
                 createUser·p0.999:  21.791 ms/op
                 createUser·p0.9999: 37.736 ms/op
                 createUser·p1.00:   39.846 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  19.278 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270551
  mean =      3.549 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4671 
    [ 2.500,  5.000) = 257034 
    [ 5.000,  7.500) = 7173 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     20.527 ms/op
     p(99.9900) =     35.386 ms/op
     p(99.9990) =     38.508 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.558 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.012 ms/op
Iteration   1: 3.363 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  21.463 ms/op
                 existUser·p0.9999: 24.690 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  22.944 ms/op
                 existUser·p0.9999: 25.522 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.384 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  14.976 ms/op
                 existUser·p0.9999: 29.724 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283382
  mean =      3.386 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5803 
    [ 2.500,  5.000) = 269962 
    [ 5.000,  7.500) = 5955 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     18.434 ms/op
     p(99.9900) =     27.448 ms/op
     p(99.9990) =     31.550 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 10.146 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.013 ms/op
Iteration   1: 3.690 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.959 ms/op
                 getUser·p0.999:  20.131 ms/op
                 getUser·p0.9999: 28.061 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.605 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  23.828 ms/op
                 getUser·p0.9999: 26.525 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.600 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 27.602 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264285
  mean =      3.631 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2139 
    [ 2.500,  5.000) = 250195 
    [ 5.000,  7.500) = 8755 
    [ 7.500, 10.000) = 2198 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     21.519 ms/op
     p(99.9900) =     27.642 ms/op
     p(99.9990) =     28.698 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 12.392 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.671 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.016 ms/op
Iteration   1: 4.342 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  23.003 ms/op
                 listUser·p0.9999: 27.693 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 4.292 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  18.270 ms/op
                 listUser·p0.9999: 24.780 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 4.287 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 20.498 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222658
  mean =      4.307 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 207995 
    [ 5.000,  7.500) = 10271 
    [ 7.500, 10.000) = 2806 
    [10.000, 12.500) = 692 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 369 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     25.791 ms/op
     p(99.9990) =     29.771 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.092 ± 1.800  ops/ms
ClientPb.existUser                       thrpt       3   9.512 ± 2.587  ops/ms
ClientPb.getUser                         thrpt       3   9.099 ± 5.276  ops/ms
ClientPb.listUser                        thrpt       3   7.460 ± 0.735  ops/ms
ClientPb.createUser                       avgt       3   3.645 ± 2.488   ms/op
ClientPb.existUser                        avgt       3   3.423 ± 0.921   ms/op
ClientPb.getUser                          avgt       3   3.478 ± 0.104   ms/op
ClientPb.listUser                         avgt       3   4.171 ± 1.314   ms/op
ClientPb.createUser                     sample  270551   3.549 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.527           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.846           ms/op
ClientPb.existUser                      sample  283382   3.386 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.434           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.448           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  264285   3.631 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.519           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.642           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  222658   4.307 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.350           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.791           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.819           ms/op
