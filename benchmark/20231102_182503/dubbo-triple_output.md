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
# Warmup Iteration   1: 0.969 ops/ms
# Warmup Iteration   2: 2.090 ops/ms
# Warmup Iteration   3: 5.206 ops/ms
Iteration   1: 5.192 ops/ms
Iteration   2: 5.620 ops/ms
Iteration   3: 5.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.468 ±(99.9%) 4.361 ops/ms [Average]
  (min, avg, max) = (5.192, 5.468, 5.620), stdev = 0.239
  CI (99.9%): [1.107, 9.829] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.358 ops/ms
# Warmup Iteration   2: 4.204 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 5.784 ops/ms
Iteration   2: 5.785 ops/ms
Iteration   3: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.786 ±(99.9%) 0.046 ops/ms [Average]
  (min, avg, max) = (5.784, 5.786, 5.789), stdev = 0.003
  CI (99.9%): [5.740, 5.833] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.671 ops/ms
# Warmup Iteration   2: 4.279 ops/ms
# Warmup Iteration   3: 5.574 ops/ms
Iteration   1: 5.352 ops/ms
Iteration   2: 5.491 ops/ms
Iteration   3: 5.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.459 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (5.352, 5.459, 5.535), stdev = 0.096
  CI (99.9%): [3.717, 7.202] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.438 ops/ms
# Warmup Iteration   2: 3.825 ops/ms
# Warmup Iteration   3: 4.757 ops/ms
Iteration   1: 4.765 ops/ms
Iteration   2: 4.785 ops/ms
Iteration   3: 4.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.785 ±(99.9%) 0.365 ops/ms [Average]
  (min, avg, max) = (4.765, 4.785, 4.805), stdev = 0.020
  CI (99.9%): [4.420, 5.151] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 19.399 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.999 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.985 ±(99.9%) 0.013 ms/op
Iteration   1: 5.818 ±(99.9%) 0.007 ms/op
Iteration   2: 5.421 ±(99.9%) 0.015 ms/op
Iteration   3: 5.613 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.617 ±(99.9%) 3.616 ms/op [Average]
  (min, avg, max) = (5.421, 5.617, 5.818), stdev = 0.198
  CI (99.9%): [2.001, 9.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.904 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.750 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.513 ±(99.9%) 0.007 ms/op
Iteration   1: 5.516 ±(99.9%) 0.008 ms/op
Iteration   2: 5.444 ±(99.9%) 0.008 ms/op
Iteration   3: 5.621 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.527 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (5.444, 5.527, 5.621), stdev = 0.089
  CI (99.9%): [3.898, 7.156] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.195 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.808 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.926 ±(99.9%) 0.011 ms/op
Iteration   1: 6.028 ±(99.9%) 0.007 ms/op
Iteration   2: 5.759 ±(99.9%) 0.008 ms/op
Iteration   3: 5.519 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.769 ±(99.9%) 4.645 ms/op [Average]
  (min, avg, max) = (5.519, 5.769, 6.028), stdev = 0.255
  CI (99.9%): [1.124, 10.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.693 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 8.636 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.732 ±(99.9%) 0.009 ms/op
Iteration   1: 6.575 ±(99.9%) 0.010 ms/op
Iteration   2: 6.656 ±(99.9%) 0.016 ms/op
Iteration   3: 6.526 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.585 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (6.526, 6.585, 6.656), stdev = 0.066
  CI (99.9%): [5.390, 7.781] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.899 ±(99.9%) 0.372 ms/op
# Warmup Iteration   2: 7.935 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 5.986 ±(99.9%) 0.028 ms/op
Iteration   1: 5.813 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   7.381 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.420 ms/op
                 createUser·p0.999:  25.558 ms/op
                 createUser·p0.9999: 33.784 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   2: 5.909 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   2.068 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.684 ms/op
                 createUser·p0.95:   9.683 ms/op
                 createUser·p0.99:   14.318 ms/op
                 createUser·p0.999:  28.031 ms/op
                 createUser·p0.9999: 32.230 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 5.742 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.960 ms/op
                 createUser·p0.999:  29.819 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164798
  mean =      5.820 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 52587 
    [ 5.000,  7.500) = 96963 
    [ 7.500, 10.000) = 10602 
    [10.000, 12.500) = 2820 
    [12.500, 15.000) = 1073 
    [15.000, 17.500) = 279 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 80 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     28.318 ms/op
     p(99.9900) =     33.278 ms/op
     p(99.9990) =     34.345 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.157 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.530 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.612 ±(99.9%) 0.024 ms/op
Iteration   1: 5.450 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   8.102 ms/op
                 existUser·p0.99:   12.354 ms/op
                 existUser·p0.999:  15.619 ms/op
                 existUser·p0.9999: 27.427 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 5.570 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.004 ms/op
                 existUser·p0.99:   10.846 ms/op
                 existUser·p0.999:  28.285 ms/op
                 existUser·p0.9999: 35.455 ms/op
                 existUser·p1.00:   35.521 ms/op

Iteration   3: 5.485 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   8.126 ms/op
                 existUser·p0.99:   12.288 ms/op
                 existUser·p0.999:  27.146 ms/op
                 existUser·p0.9999: 29.781 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174449
  mean =      5.501 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 76362 
    [ 5.000,  7.500) = 86197 
    [ 7.500, 10.000) = 8417 
    [10.000, 12.500) = 2096 
    [12.500, 15.000) = 955 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     19.679 ms/op
     p(99.9900) =     32.972 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.491 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.997 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.898 ±(99.9%) 0.026 ms/op
Iteration   1: 6.198 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.617 ms/op
                 getUser·p0.50:   5.579 ms/op
                 getUser·p0.90:   8.651 ms/op
                 getUser·p0.95:   10.142 ms/op
                 getUser·p0.99:   14.057 ms/op
                 getUser·p0.999:  27.520 ms/op
                 getUser·p0.9999: 30.759 ms/op
                 getUser·p1.00:   31.425 ms/op

Iteration   2: 5.834 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.892 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.782 ms/op
                 getUser·p0.95:   9.093 ms/op
                 getUser·p0.99:   12.845 ms/op
                 getUser·p0.999:  18.299 ms/op
                 getUser·p0.9999: 36.668 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   3: 5.746 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.365 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   12.567 ms/op
                 getUser·p0.999:  28.180 ms/op
                 getUser·p0.9999: 32.061 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162066
  mean =      5.920 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 46652 
    [ 5.000,  7.500) = 96163 
    [ 7.500, 10.000) = 13578 
    [10.000, 12.500) = 3463 
    [12.500, 15.000) = 1331 
    [15.000, 17.500) = 504 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     13.271 ms/op
     p(99.9000) =     27.062 ms/op
     p(99.9900) =     34.248 ms/op
     p(99.9990) =     36.906 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.391 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 8.672 ±(99.9%) 0.079 ms/op
# Warmup Iteration   3: 6.981 ±(99.9%) 0.030 ms/op
Iteration   1: 6.913 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.303 ms/op
                 listUser·p0.999:  28.131 ms/op
                 listUser·p0.9999: 30.999 ms/op
                 listUser·p1.00:   31.293 ms/op

Iteration   2: 6.911 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.023 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.387 ms/op
                 listUser·p0.99:   14.090 ms/op
                 listUser·p0.999:  31.809 ms/op
                 listUser·p0.9999: 34.406 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   3: 6.708 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.329 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  28.312 ms/op
                 listUser·p0.9999: 35.682 ms/op
                 listUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140195
  mean =      6.843 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 3786 
    [ 5.000,  7.500) = 108470 
    [ 7.500, 10.000) = 20044 
    [10.000, 12.500) = 5428 
    [12.500, 15.000) = 1586 
    [15.000, 17.500) = 455 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      6.357 ms/op
     p(90.0000) =      8.815 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     14.008 ms/op
     p(99.9000) =     29.354 ms/op
     p(99.9900) =     34.405 ms/op
     p(99.9990) =     36.150 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.468 ± 4.361  ops/ms
ClientPb.existUser                       thrpt       3   5.786 ± 0.046  ops/ms
ClientPb.getUser                         thrpt       3   5.459 ± 1.743  ops/ms
ClientPb.listUser                        thrpt       3   4.785 ± 0.365  ops/ms
ClientPb.createUser                       avgt       3   5.617 ± 3.616   ms/op
ClientPb.existUser                        avgt       3   5.527 ± 1.629   ms/op
ClientPb.getUser                          avgt       3   5.769 ± 4.645   ms/op
ClientPb.listUser                         avgt       3   6.585 ± 1.196   ms/op
ClientPb.createUser                     sample  164798   5.820 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.602           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.730           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.318           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.278           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  174449   5.501 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.069           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.846           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.679           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.972           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  162066   5.920 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.856           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.290           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.271           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.248           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  140195   6.843 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.305           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.357           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.240           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.008           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.354           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.176           ms/op
