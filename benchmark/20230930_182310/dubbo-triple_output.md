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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.302 ops/ms
# Warmup Iteration   3: 8.271 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 9.010 ops/ms
Iteration   3: 8.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.929 ±(99.9%) 2.247 ops/ms [Average]
  (min, avg, max) = (8.787, 8.929, 9.010), stdev = 0.123
  CI (99.9%): [6.681, 11.176] (assumes normal distribution)


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
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 8.955 ops/ms
# Warmup Iteration   3: 9.491 ops/ms
Iteration   1: 9.654 ops/ms
Iteration   2: 9.531 ops/ms
Iteration   3: 9.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.626 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (9.531, 9.626, 9.695), stdev = 0.086
  CI (99.9%): [8.066, 11.187] (assumes normal distribution)


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
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 7.843 ops/ms
# Warmup Iteration   3: 8.816 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.209 ops/ms
Iteration   3: 9.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.206 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (9.160, 9.206, 9.250), stdev = 0.045
  CI (99.9%): [8.387, 10.026] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.764 ops/ms
# Warmup Iteration   2: 6.962 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.597 ops/ms
Iteration   2: 7.637 ops/ms
Iteration   3: 7.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.641 ±(99.9%) 0.834 ops/ms [Average]
  (min, avg, max) = (7.597, 7.641, 7.688), stdev = 0.046
  CI (99.9%): [6.807, 8.475] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.873 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.005 ms/op
Iteration   1: 3.561 ±(99.9%) 0.005 ms/op
Iteration   2: 3.444 ±(99.9%) 0.005 ms/op
Iteration   3: 3.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.531 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (3.444, 3.531, 3.589), stdev = 0.077
  CI (99.9%): [2.126, 4.937] (assumes normal distribution)


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
# Warmup Iteration   1: 7.287 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.006 ms/op
Iteration   1: 3.307 ±(99.9%) 0.005 ms/op
Iteration   2: 3.386 ±(99.9%) 0.006 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.340 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.307, 3.340, 3.386), stdev = 0.041
  CI (99.9%): [2.591, 4.090] (assumes normal distribution)


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
# Warmup Iteration   1: 8.818 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.006 ms/op
Iteration   1: 3.612 ±(99.9%) 0.004 ms/op
Iteration   2: 3.471 ±(99.9%) 0.007 ms/op
Iteration   3: 3.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.471, 3.540, 3.612), stdev = 0.071
  CI (99.9%): [2.248, 4.832] (assumes normal distribution)


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
# Warmup Iteration   1: 10.317 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.005 ms/op
Iteration   1: 4.053 ±(99.9%) 0.006 ms/op
Iteration   2: 4.106 ±(99.9%) 0.008 ms/op
Iteration   3: 4.167 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.109 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (4.053, 4.109, 4.167), stdev = 0.057
  CI (99.9%): [3.067, 5.150] (assumes normal distribution)


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
# Warmup Iteration   1: 9.418 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.011 ms/op
Iteration   1: 3.559 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.769 ms/op
                 createUser·p0.999:  20.579 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.246 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 25.688 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.470 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 30.866 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271039
  mean =      3.541 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5771 
    [ 2.500,  5.000) = 254865 
    [ 5.000,  7.500) = 8413 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     18.315 ms/op
     p(99.9900) =     30.373 ms/op
     p(99.9990) =     31.678 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 9.393 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.316 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  20.021 ms/op
                 existUser·p0.9999: 23.703 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.409 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  20.782 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  17.696 ms/op
                 existUser·p0.9999: 23.572 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286517
  mean =      3.348 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10528 
    [ 2.500,  5.000) = 266263 
    [ 5.000,  7.500) = 8259 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.765 ms/op
     p(99.9000) =     18.725 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     24.253 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 8.628 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.012 ms/op
Iteration   1: 3.638 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  21.207 ms/op
                 getUser·p0.9999: 30.441 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.125 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 22.665 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.868 ms/op
                 getUser·p0.999:  15.757 ms/op
                 getUser·p0.9999: 23.455 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272214
  mean =      3.524 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3506 
    [ 2.500,  5.000) = 257546 
    [ 5.000,  7.500) = 9310 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 184 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     30.791 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.047 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.013 ms/op
Iteration   1: 4.120 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  17.193 ms/op
                 listUser·p0.9999: 23.863 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 4.242 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 18.431 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.105 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.856 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 22.519 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230893
  mean =      4.155 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 220392 
    [ 5.000,  7.500) = 7642 
    [ 7.500, 10.000) = 1955 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.901 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     15.419 ms/op
     p(99.9900) =     22.574 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.929 ± 2.247  ops/ms
ClientPb.existUser                       thrpt       3   9.626 ± 1.560  ops/ms
ClientPb.getUser                         thrpt       3   9.206 ± 0.819  ops/ms
ClientPb.listUser                        thrpt       3   7.641 ± 0.834  ops/ms
ClientPb.createUser                       avgt       3   3.531 ± 1.406   ms/op
ClientPb.existUser                        avgt       3   3.340 ± 0.750   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 1.292   ms/op
ClientPb.listUser                         avgt       3   4.109 ± 1.042   ms/op
ClientPb.createUser                     sample  271039   3.541 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.315           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.373           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.949           ms/op
ClientPb.existUser                      sample  286517   3.348 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.765           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.725           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.495           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  272214   3.524 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.283           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.999           ms/op
ClientPb.listUser                       sample  230893   4.155 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.901           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.419           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
