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
# Warmup Iteration   1: 1.901 ops/ms
# Warmup Iteration   2: 5.085 ops/ms
# Warmup Iteration   3: 7.555 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 8.261 ops/ms
Iteration   3: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.082 ±(99.9%) 5.672 ops/ms [Average]
  (min, avg, max) = (7.723, 8.082, 8.262), stdev = 0.311
  CI (99.9%): [2.411, 13.754] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 7.711 ops/ms
# Warmup Iteration   3: 8.253 ops/ms
Iteration   1: 8.697 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.621 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (8.515, 8.621, 8.697), stdev = 0.094
  CI (99.9%): [6.899, 10.343] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 7.079 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 8.399 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.259 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (8.182, 8.259, 8.399), stdev = 0.121
  CI (99.9%): [6.047, 10.470] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.923 ops/ms
# Warmup Iteration   3: 6.673 ops/ms
Iteration   1: 7.062 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 7.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.988 ±(99.9%) 3.396 ops/ms [Average]
  (min, avg, max) = (6.777, 6.988, 7.126), stdev = 0.186
  CI (99.9%): [3.593, 10.384] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.448 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.006 ms/op
Iteration   1: 4.164 ±(99.9%) 0.006 ms/op
Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
Iteration   3: 3.994 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.021 ±(99.9%) 2.402 ms/op [Average]
  (min, avg, max) = (3.904, 4.021, 4.164), stdev = 0.132
  CI (99.9%): [1.618, 6.423] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.140 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.008 ms/op
Iteration   1: 3.645 ±(99.9%) 0.004 ms/op
Iteration   2: 3.643 ±(99.9%) 0.005 ms/op
Iteration   3: 3.971 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.753 ±(99.9%) 3.447 ms/op [Average]
  (min, avg, max) = (3.643, 3.753, 3.971), stdev = 0.189
  CI (99.9%): [0.306, 7.200] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.901 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.004 ms/op
Iteration   1: 3.798 ±(99.9%) 0.005 ms/op
Iteration   2: 3.834 ±(99.9%) 0.005 ms/op
Iteration   3: 3.901 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.844 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (3.798, 3.844, 3.901), stdev = 0.052
  CI (99.9%): [2.898, 4.791] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.082 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.602 ±(99.9%) 0.008 ms/op
Iteration   1: 4.513 ±(99.9%) 0.011 ms/op
Iteration   2: 4.412 ±(99.9%) 0.013 ms/op
Iteration   3: 4.554 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.493 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (4.412, 4.493, 4.554), stdev = 0.073
  CI (99.9%): [3.167, 5.819] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.176 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.020 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  12.096 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.965 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  23.055 ms/op
                 createUser·p0.9999: 25.000 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.973 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  25.899 ms/op
                 createUser·p0.9999: 32.904 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242740
  mean =      3.956 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1065 
    [ 2.500,  5.000) = 227113 
    [ 5.000,  7.500) = 11986 
    [ 7.500, 10.000) = 1683 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     33.096 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 10.935 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.013 ms/op
Iteration   1: 3.729 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.041 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 24.459 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 3.905 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  24.484 ms/op
                 existUser·p0.9999: 28.522 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 3.726 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  12.078 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253454
  mean =      3.785 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 978 
    [ 2.500,  5.000) = 241209 
    [ 5.000,  7.500) = 8658 
    [ 7.500, 10.000) = 1740 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     31.412 ms/op
     p(99.9990) =     34.502 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 12.316 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.014 ms/op
Iteration   1: 4.015 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  22.938 ms/op
                 getUser·p0.9999: 25.796 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 3.899 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  25.455 ms/op
                 getUser·p0.9999: 30.120 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 3.917 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 41.746 ms/op
                 getUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243325
  mean =      3.943 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228854 
    [ 5.000, 10.000) = 13640 
    [10.000, 15.000) = 508 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     22.851 ms/op
     p(99.9900) =     41.004 ms/op
     p(99.9990) =     41.980 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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
# Warmup Iteration   1: 13.032 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.697 ±(99.9%) 0.016 ms/op
Iteration   1: 4.770 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  24.705 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   31.130 ms/op

Iteration   2: 4.580 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  16.882 ms/op
                 listUser·p0.9999: 21.760 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.622 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 27.689 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206081
  mean =      4.656 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 175718 
    [ 5.000,  7.500) = 24429 
    [ 7.500, 10.000) = 4485 
    [10.000, 12.500) = 868 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     18.052 ms/op
     p(99.9900) =     27.636 ms/op
     p(99.9990) =     30.987 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.082 ± 5.672  ops/ms
ClientPb.existUser                       thrpt       3   8.621 ± 1.722  ops/ms
ClientPb.getUser                         thrpt       3   8.259 ± 2.212  ops/ms
ClientPb.listUser                        thrpt       3   6.988 ± 3.396  ops/ms
ClientPb.createUser                       avgt       3   4.021 ± 2.402   ms/op
ClientPb.existUser                        avgt       3   3.753 ± 3.447   ms/op
ClientPb.getUser                          avgt       3   3.844 ± 0.947   ms/op
ClientPb.listUser                         avgt       3   4.493 ± 1.326   ms/op
ClientPb.createUser                     sample  242740   3.956 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.065           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.602           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.688           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  253454   3.785 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.561           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  243325   3.943 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.709           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.851           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.004           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.140           ms/op
ClientPb.listUser                       sample  206081   4.656 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.052           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.636           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.130           ms/op
