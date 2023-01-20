# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 4.928 ops/ms
# Warmup Iteration   3: 8.369 ops/ms
Iteration   1: 9.183 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 9.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.289 ±(99.9%) 2.832 ops/ms [Average]
  (min, avg, max) = (9.183, 9.289, 9.467), stdev = 0.155
  CI (99.9%): [6.457, 12.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 9.554 ops/ms
# Warmup Iteration   3: 10.502 ops/ms
Iteration   1: 10.215 ops/ms
Iteration   2: 10.236 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.133 ±(99.9%) 2.925 ops/ms [Average]
  (min, avg, max) = (9.948, 10.133, 10.236), stdev = 0.160
  CI (99.9%): [7.208, 13.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.309 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.690 ±(99.9%) 9.717 ops/ms [Average]
  (min, avg, max) = (9.309, 9.690, 10.299), stdev = 0.533
  CI (99.9%): [≈ 0, 19.407] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 7.289 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 8.409 ops/ms
Iteration   3: 8.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.716 ±(99.9%) 7.796 ops/ms [Average]
  (min, avg, max) = (8.409, 8.716, 9.204), stdev = 0.427
  CI (99.9%): [0.920, 16.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.792 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.004 ms/op
Iteration   1: 3.405 ±(99.9%) 0.011 ms/op
Iteration   2: 3.509 ±(99.9%) 0.004 ms/op
Iteration   3: 3.312 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.409 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (3.312, 3.409, 3.509), stdev = 0.099
  CI (99.9%): [1.611, 5.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.071 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.009 ms/op
Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
Iteration   3: 3.248 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.239 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.226, 3.239, 3.248), stdev = 0.011
  CI (99.9%): [3.030, 3.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.216 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.003 ms/op
Iteration   1: 3.349 ±(99.9%) 0.006 ms/op
Iteration   2: 3.486 ±(99.9%) 0.008 ms/op
Iteration   3: 3.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.429 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.349, 3.429, 3.486), stdev = 0.071
  CI (99.9%): [2.129, 4.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.229 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.008 ms/op
Iteration   1: 3.958 ±(99.9%) 0.005 ms/op
Iteration   2: 3.984 ±(99.9%) 0.008 ms/op
Iteration   3: 3.718 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.886 ±(99.9%) 2.669 ms/op [Average]
  (min, avg, max) = (3.718, 3.886, 3.984), stdev = 0.146
  CI (99.9%): [1.217, 6.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.574 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  20.961 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.274 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.967 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  19.477 ms/op
                 createUser·p0.9999: 29.950 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  18.074 ms/op
                 createUser·p0.9999: 22.383 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288976
  mean =      3.324 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7821 
    [ 2.500,  5.000) = 275812 
    [ 5.000,  7.500) = 4436 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     19.926 ms/op
     p(99.9900) =     28.181 ms/op
     p(99.9990) =     30.518 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.459 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  10.418 ms/op
                 existUser·p0.9999: 27.983 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  16.960 ms/op
                 existUser·p0.9999: 25.505 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  14.404 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300822
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6326 
    [ 2.500,  5.000) = 288790 
    [ 5.000,  7.500) = 4803 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.129 ms/op
     p(99.9900) =     27.938 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.938 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.013 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  13.150 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.151 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  19.933 ms/op
                 getUser·p0.9999: 26.199 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292256
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6415 
    [ 2.500,  5.000) = 279443 
    [ 5.000,  7.500) = 5486 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.849 ms/op
     p(99.9900) =     24.667 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.630 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
Iteration   1: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.020 ms/op
                 listUser·p0.9999: 20.925 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.824 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.876 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.851 ms/op
                 listUser·p0.9999: 15.912 ms/op
                 listUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250584
  mean =      3.833 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 243170 
    [ 5.000,  7.500) = 5534 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     19.790 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.289 ± 2.832  ops/ms
ClientPb.existUser                       thrpt       3  10.133 ± 2.925  ops/ms
ClientPb.getUser                         thrpt       3   9.690 ± 9.717  ops/ms
ClientPb.listUser                        thrpt       3   8.716 ± 7.796  ops/ms
ClientPb.createUser                       avgt       3   3.409 ± 1.798   ms/op
ClientPb.existUser                        avgt       3   3.239 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   3.429 ± 1.299   ms/op
ClientPb.listUser                         avgt       3   3.886 ± 2.669   ms/op
ClientPb.createUser                     sample  288976   3.324 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.043           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.181           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  300822   3.188 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.129           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.917           ms/op
ClientPb.getUser                        sample  292256   3.281 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.902           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.849           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.667           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.148           ms/op
ClientPb.listUser                       sample  250584   3.833 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.023           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
