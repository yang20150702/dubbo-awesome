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
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 5.403 ops/ms
# Warmup Iteration   3: 8.367 ops/ms
Iteration   1: 8.846 ops/ms
Iteration   2: 8.904 ops/ms
Iteration   3: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.902 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (8.846, 8.902, 8.957), stdev = 0.056
  CI (99.9%): [7.887, 9.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.948 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.262 ops/ms
Iteration   1: 9.768 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.550 ±(99.9%) 3.463 ops/ms [Average]
  (min, avg, max) = (9.421, 9.550, 9.768), stdev = 0.190
  CI (99.9%): [6.087, 13.013] (assumes normal distribution)


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
# Warmup Iteration   1: 3.105 ops/ms
# Warmup Iteration   2: 8.734 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.183 ops/ms
Iteration   2: 8.888 ops/ms
Iteration   3: 8.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.962 ±(99.9%) 3.549 ops/ms [Average]
  (min, avg, max) = (8.815, 8.962, 9.183), stdev = 0.195
  CI (99.9%): [5.413, 12.511] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 6.888 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.713 ops/ms
Iteration   3: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.795 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (7.713, 7.795, 7.914), stdev = 0.105
  CI (99.9%): [5.871, 9.719] (assumes normal distribution)


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
# Warmup Iteration   1: 10.425 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.004 ms/op
Iteration   1: 3.437 ±(99.9%) 0.003 ms/op
Iteration   2: 3.504 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.461 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (3.437, 3.461, 3.504), stdev = 0.037
  CI (99.9%): [2.791, 4.132] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.296 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.008 ms/op
Iteration   1: 3.508 ±(99.9%) 0.007 ms/op
Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
Iteration   3: 3.476 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.430 ±(99.9%) 1.958 ms/op [Average]
  (min, avg, max) = (3.308, 3.430, 3.508), stdev = 0.107
  CI (99.9%): [1.472, 5.389] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.763 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.007 ms/op
Iteration   1: 3.550 ±(99.9%) 0.004 ms/op
Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
Iteration   3: 3.376 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.376, 3.456, 3.550), stdev = 0.088
  CI (99.9%): [1.859, 5.052] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.012 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.007 ms/op
Iteration   1: 4.105 ±(99.9%) 0.009 ms/op
Iteration   2: 4.046 ±(99.9%) 0.008 ms/op
Iteration   3: 4.108 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (4.046, 4.086, 4.108), stdev = 0.035
  CI (99.9%): [3.448, 4.724] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.668 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.014 ms/op
Iteration   1: 3.563 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  22.486 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  22.399 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.509 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  20.860 ms/op
                 createUser·p0.9999: 31.187 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273408
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6969 
    [ 2.500,  5.000) = 258179 
    [ 5.000,  7.500) = 6588 
    [ 7.500, 10.000) = 1043 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     21.220 ms/op
     p(99.9900) =     29.730 ms/op
     p(99.9990) =     31.859 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.632 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.624 ms/op
                 existUser·p0.999:  21.168 ms/op
                 existUser·p0.9999: 23.082 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  12.872 ms/op
                 existUser·p0.9999: 23.253 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.343 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  23.206 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284180
  mean =      3.376 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7477 
    [ 2.500,  5.000) = 268921 
    [ 5.000,  7.500) = 6066 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     33.434 ms/op
     p(99.9990) =     34.220 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 10.170 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.011 ms/op
Iteration   1: 3.606 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.718 ms/op
                 getUser·p0.999:  21.163 ms/op
                 getUser·p0.9999: 32.969 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  22.833 ms/op
                 getUser·p0.9999: 25.979 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  19.549 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270869
  mean =      3.544 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4119 
    [ 2.500,  5.000) = 255374 
    [ 5.000,  7.500) = 9049 
    [ 7.500, 10.000) = 1640 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     20.300 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     35.225 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 11.999 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.014 ms/op
Iteration   1: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  19.423 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  15.511 ms/op
                 listUser·p0.9999: 18.869 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.119 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233104
  mean =      4.112 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 222525 
    [ 5.000,  7.500) = 6820 
    [ 7.500, 10.000) = 2490 
    [10.000, 12.500) = 615 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     15.825 ms/op
     p(99.9900) =     24.623 ms/op
     p(99.9990) =     27.536 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.902 ± 1.015  ops/ms
ClientPb.existUser                       thrpt       3   9.550 ± 3.463  ops/ms
ClientPb.getUser                         thrpt       3   8.962 ± 3.549  ops/ms
ClientPb.listUser                        thrpt       3   7.795 ± 1.924  ops/ms
ClientPb.createUser                       avgt       3   3.461 ± 0.670   ms/op
ClientPb.existUser                        avgt       3   3.430 ± 1.958   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 1.596   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 0.638   ms/op
ClientPb.createUser                     sample  273408   3.511 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.762           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.570           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.220           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  284180   3.376 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.709           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.761           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.434           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  270869   3.544 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.300           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.997           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  233104   4.112 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.825           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
