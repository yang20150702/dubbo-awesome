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
# Warmup Iteration   1: 1.874 ops/ms
# Warmup Iteration   2: 3.967 ops/ms
# Warmup Iteration   3: 7.354 ops/ms
Iteration   1: 7.502 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.780 ±(99.9%) 4.434 ops/ms [Average]
  (min, avg, max) = (7.502, 7.780, 7.949), stdev = 0.243
  CI (99.9%): [3.346, 12.215] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 6.436 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.305 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.331 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (8.251, 8.331, 8.437), stdev = 0.096
  CI (99.9%): [6.585, 10.077] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.274 ops/ms
# Warmup Iteration   2: 7.289 ops/ms
# Warmup Iteration   3: 7.614 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 7.813 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.967 ±(99.9%) 2.838 ops/ms [Average]
  (min, avg, max) = (7.813, 7.967, 8.124), stdev = 0.156
  CI (99.9%): [5.129, 10.805] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.635 ops/ms
# Warmup Iteration   3: 6.485 ops/ms
Iteration   1: 6.640 ops/ms
Iteration   2: 6.494 ops/ms
Iteration   3: 6.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.637 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (6.494, 6.637, 6.776), stdev = 0.141
  CI (99.9%): [4.064, 9.210] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.085 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.006 ms/op
Iteration   1: 4.125 ±(99.9%) 0.007 ms/op
Iteration   2: 4.084 ±(99.9%) 0.006 ms/op
Iteration   3: 4.010 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.073 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (4.010, 4.073, 4.125), stdev = 0.059
  CI (99.9%): [3.002, 5.144] (assumes normal distribution)


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
# Warmup Iteration   1: 13.017 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.005 ms/op
Iteration   1: 3.914 ±(99.9%) 0.008 ms/op
Iteration   2: 3.830 ±(99.9%) 0.004 ms/op
Iteration   3: 3.893 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.830, 3.879, 3.914), stdev = 0.044
  CI (99.9%): [3.079, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 13.296 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.004 ms/op
Iteration   1: 4.128 ±(99.9%) 0.006 ms/op
Iteration   2: 4.121 ±(99.9%) 0.006 ms/op
Iteration   3: 3.963 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.071 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.963, 4.071, 4.128), stdev = 0.093
  CI (99.9%): [2.367, 5.774] (assumes normal distribution)


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
# Warmup Iteration   1: 14.284 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.010 ms/op
Iteration   1: 4.720 ±(99.9%) 0.009 ms/op
Iteration   2: 4.749 ±(99.9%) 0.010 ms/op
Iteration   3: 4.820 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.763 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (4.720, 4.763, 4.820), stdev = 0.051
  CI (99.9%): [3.824, 5.702] (assumes normal distribution)


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
# Warmup Iteration   1: 12.848 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.719 ±(99.9%) 0.023 ms/op
Iteration   1: 4.171 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  17.399 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 4.041 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  27.582 ms/op
                 createUser·p0.9999: 48.497 ms/op
                 createUser·p1.00:   49.742 ms/op

Iteration   3: 4.093 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   8.054 ms/op
                 createUser·p0.999:  27.623 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234070
  mean =      4.101 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 219434 
    [ 5.000, 10.000) = 13818 
    [10.000, 15.000) = 495 
    [15.000, 20.000) = 67 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 153 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     25.819 ms/op
     p(99.9900) =     44.249 ms/op
     p(99.9990) =     49.064 ms/op
     p(99.9999) =     49.742 ms/op
    p(100.0000) =     49.742 ms/op


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
# Warmup Iteration   1: 12.993 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.014 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  13.259 ms/op
                 existUser·p0.9999: 25.918 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.935 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 36.307 ms/op
                 existUser·p1.00:   37.552 ms/op

Iteration   3: 3.913 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.036 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   8.811 ms/op
                 existUser·p0.999:  16.974 ms/op
                 existUser·p0.9999: 32.522 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243178
  mean =      3.945 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185 
    [ 2.500,  5.000) = 229271 
    [ 5.000,  7.500) = 11271 
    [ 7.500, 10.000) = 1554 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     35.565 ms/op
     p(99.9990) =     37.093 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 13.083 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.870 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.014 ms/op
Iteration   1: 4.229 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   6.685 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  23.113 ms/op
                 getUser·p0.9999: 26.065 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 4.098 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   8.176 ms/op
                 getUser·p0.999:  14.058 ms/op
                 getUser·p0.9999: 28.881 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 4.103 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   8.849 ms/op
                 getUser·p0.999:  27.168 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231618
  mean =      4.143 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 212417 
    [ 5.000,  7.500) = 14053 
    [ 7.500, 10.000) = 3716 
    [10.000, 12.500) = 855 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     29.224 ms/op
     p(99.9990) =     30.443 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 13.084 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.787 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.887 ±(99.9%) 0.018 ms/op
Iteration   1: 4.882 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   10.070 ms/op
                 listUser·p0.999:  23.674 ms/op
                 listUser·p0.9999: 26.222 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.907 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  21.546 ms/op
                 listUser·p0.9999: 24.297 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.886 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  17.744 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196281
  mean =      4.892 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 156310 
    [ 5.000,  7.500) = 32375 
    [ 7.500, 10.000) = 5536 
    [10.000, 12.500) = 1266 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     21.028 ms/op
     p(99.9900) =     25.256 ms/op
     p(99.9990) =     26.972 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.780 ± 4.434  ops/ms
ClientPb.existUser                       thrpt       3   8.331 ± 1.746  ops/ms
ClientPb.getUser                         thrpt       3   7.967 ± 2.838  ops/ms
ClientPb.listUser                        thrpt       3   6.637 ± 2.573  ops/ms
ClientPb.createUser                       avgt       3   4.073 ± 1.071   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 0.800   ms/op
ClientPb.getUser                          avgt       3   4.071 ± 1.703   ms/op
ClientPb.listUser                         avgt       3   4.763 ± 0.939   ms/op
ClientPb.createUser                     sample  234070   4.101 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.819           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.249           ms/op
ClientPb.createUser:createUser·p1.00    sample          49.742           ms/op
ClientPb.existUser                      sample  243178   3.945 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.563           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.520           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.565           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.552           ms/op
ClientPb.getUser                        sample  231618   4.143 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.554           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.716           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.200           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.224           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  196281   4.892 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.076           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
