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
# Warmup Iteration   1: 1.207 ops/ms
# Warmup Iteration   2: 2.705 ops/ms
# Warmup Iteration   3: 5.689 ops/ms
Iteration   1: 5.717 ops/ms
Iteration   2: 6.161 ops/ms
Iteration   3: 6.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.042 ±(99.9%) 5.206 ops/ms [Average]
  (min, avg, max) = (5.717, 6.042, 6.249), stdev = 0.285
  CI (99.9%): [0.837, 11.248] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.914 ops/ms
# Warmup Iteration   2: 5.124 ops/ms
# Warmup Iteration   3: 6.137 ops/ms
Iteration   1: 6.513 ops/ms
Iteration   2: 6.315 ops/ms
Iteration   3: 6.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.359 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (6.248, 6.359, 6.513), stdev = 0.138
  CI (99.9%): [3.850, 8.868] (assumes normal distribution)


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
# Warmup Iteration   1: 1.921 ops/ms
# Warmup Iteration   2: 4.845 ops/ms
# Warmup Iteration   3: 5.847 ops/ms
Iteration   1: 5.973 ops/ms
Iteration   2: 6.155 ops/ms
Iteration   3: 6.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.047 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (5.973, 6.047, 6.155), stdev = 0.096
  CI (99.9%): [4.299, 7.795] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.754 ops/ms
# Warmup Iteration   2: 4.127 ops/ms
# Warmup Iteration   3: 4.999 ops/ms
Iteration   1: 5.038 ops/ms
Iteration   2: 5.100 ops/ms
Iteration   3: 5.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.046 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (5.000, 5.046, 5.100), stdev = 0.050
  CI (99.9%): [4.128, 5.963] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.905 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.863 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.662 ±(99.9%) 0.012 ms/op
Iteration   1: 5.358 ±(99.9%) 0.014 ms/op
Iteration   2: 5.527 ±(99.9%) 0.012 ms/op
Iteration   3: 5.336 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.407 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (5.336, 5.407, 5.527), stdev = 0.105
  CI (99.9%): [3.499, 7.314] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.330 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.386 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.033 ±(99.9%) 0.014 ms/op
Iteration   1: 5.134 ±(99.9%) 0.016 ms/op
Iteration   2: 5.169 ±(99.9%) 0.012 ms/op
Iteration   3: 5.189 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.164 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (5.134, 5.164, 5.189), stdev = 0.028
  CI (99.9%): [4.659, 5.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.352 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.470 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.013 ms/op
Iteration   1: 5.282 ±(99.9%) 0.020 ms/op
Iteration   2: 5.305 ±(99.9%) 0.014 ms/op
Iteration   3: 5.134 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.240 ±(99.9%) 1.687 ms/op [Average]
  (min, avg, max) = (5.134, 5.240, 5.305), stdev = 0.092
  CI (99.9%): [3.553, 6.927] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.156 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.605 ±(99.9%) 0.010 ms/op
Iteration   1: 6.166 ±(99.9%) 0.018 ms/op
Iteration   2: 6.169 ±(99.9%) 0.018 ms/op
Iteration   3: 6.452 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.262 ±(99.9%) 2.995 ms/op [Average]
  (min, avg, max) = (6.166, 6.262, 6.452), stdev = 0.164
  CI (99.9%): [3.267, 9.258] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.750 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.525 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.812 ±(99.9%) 0.026 ms/op
Iteration   1: 5.303 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.127 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  22.527 ms/op
                 createUser·p0.9999: 28.540 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   2: 5.461 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.564 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  24.033 ms/op
                 createUser·p0.9999: 28.644 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 5.541 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  27.106 ms/op
                 createUser·p0.9999: 33.314 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176617
  mean =      5.433 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 64720 
    [ 5.000,  7.500) = 104251 
    [ 7.500, 10.000) = 6125 
    [10.000, 12.500) = 929 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.855 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     31.349 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.801 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.703 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.386 ±(99.9%) 0.019 ms/op
Iteration   1: 5.185 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.526 ms/op
                 existUser·p0.999:  19.620 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 5.233 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.314 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  16.515 ms/op
                 existUser·p0.9999: 29.389 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 5.178 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 26.539 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184637
  mean =      5.199 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 93909 
    [ 5.000,  7.500) = 84941 
    [ 7.500, 10.000) = 4206 
    [10.000, 12.500) = 1031 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     19.422 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     29.894 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.901 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.215 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.018 ms/op
Iteration   1: 5.541 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  22.259 ms/op
                 getUser·p0.9999: 32.001 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   2: 5.467 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.250 ms/op
                 getUser·p0.99:   9.650 ms/op
                 getUser·p0.999:  16.531 ms/op
                 getUser·p0.9999: 26.519 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 5.558 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.848 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  29.344 ms/op
                 getUser·p0.9999: 41.812 ms/op
                 getUser·p1.00:   43.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173708
  mean =      5.522 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 57443 
    [ 5.000, 10.000) = 114500 
    [10.000, 15.000) = 1383 
    [15.000, 20.000) = 185 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 100 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.042 ms/op
     p(99.9000) =     24.038 ms/op
     p(99.9900) =     37.658 ms/op
     p(99.9990) =     43.581 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.613 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 8.395 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.725 ±(99.9%) 0.026 ms/op
Iteration   1: 6.376 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  27.361 ms/op
                 listUser·p0.9999: 35.061 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   2: 6.491 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  29.218 ms/op
                 listUser·p0.9999: 32.375 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 6.295 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.408 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  22.932 ms/op
                 listUser·p0.9999: 31.401 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150284
  mean =      6.386 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 6071 
    [ 5.000,  7.500) = 126835 
    [ 7.500, 10.000) = 14003 
    [10.000, 12.500) = 2419 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     27.394 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     35.552 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.042 ± 5.206  ops/ms
ClientPb.existUser                       thrpt       3   6.359 ± 2.509  ops/ms
ClientPb.getUser                         thrpt       3   6.047 ± 1.748  ops/ms
ClientPb.listUser                        thrpt       3   5.046 ± 0.918  ops/ms
ClientPb.createUser                       avgt       3   5.407 ± 1.908   ms/op
ClientPb.existUser                        avgt       3   5.164 ± 0.505   ms/op
ClientPb.getUser                          avgt       3   5.240 ± 1.687   ms/op
ClientPb.listUser                         avgt       3   6.262 ± 2.995   ms/op
ClientPb.createUser                     sample  176617   5.433 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.855           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.570           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.716           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.216           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  184637   5.199 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.683           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.422           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.344           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.950           ms/op
ClientPb.getUser                        sample  173708   5.522 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.599           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.455           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.042           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.658           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.581           ms/op
ClientPb.listUser                       sample  150284   6.386 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.676           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.452           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.341           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
