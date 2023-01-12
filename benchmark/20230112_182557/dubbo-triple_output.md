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
# Warmup Iteration   1: 0.997 ops/ms
# Warmup Iteration   2: 2.168 ops/ms
# Warmup Iteration   3: 4.543 ops/ms
Iteration   1: 5.251 ops/ms
Iteration   2: 5.217 ops/ms
Iteration   3: 5.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.246 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (5.217, 5.246, 5.270), stdev = 0.027
  CI (99.9%): [4.755, 5.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.496 ops/ms
# Warmup Iteration   2: 4.107 ops/ms
# Warmup Iteration   3: 5.767 ops/ms
Iteration   1: 5.563 ops/ms
Iteration   2: 5.950 ops/ms
Iteration   3: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.768 ±(99.9%) 3.552 ops/ms [Average]
  (min, avg, max) = (5.563, 5.768, 5.950), stdev = 0.195
  CI (99.9%): [2.216, 9.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.443 ops/ms
# Warmup Iteration   2: 4.197 ops/ms
# Warmup Iteration   3: 5.579 ops/ms
Iteration   1: 5.399 ops/ms
Iteration   2: 5.587 ops/ms
Iteration   3: 5.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.509 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (5.399, 5.509, 5.587), stdev = 0.098
  CI (99.9%): [3.726, 7.292] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.262 ops/ms
# Warmup Iteration   2: 3.357 ops/ms
# Warmup Iteration   3: 4.589 ops/ms
Iteration   1: 4.609 ops/ms
Iteration   2: 4.712 ops/ms
Iteration   3: 4.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.630 ±(99.9%) 1.355 ops/ms [Average]
  (min, avg, max) = (4.568, 4.630, 4.712), stdev = 0.074
  CI (99.9%): [3.274, 5.985] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.701 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.312 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 6.003 ±(99.9%) 0.016 ms/op
Iteration   1: 5.871 ±(99.9%) 0.018 ms/op
Iteration   2: 5.783 ±(99.9%) 0.015 ms/op
Iteration   3: 5.771 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.808 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (5.771, 5.808, 5.871), stdev = 0.055
  CI (99.9%): [4.813, 6.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.523 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.190 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.015 ms/op
Iteration   1: 5.667 ±(99.9%) 0.007 ms/op
Iteration   2: 5.612 ±(99.9%) 0.009 ms/op
Iteration   3: 5.412 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.564 ±(99.9%) 2.444 ms/op [Average]
  (min, avg, max) = (5.412, 5.564, 5.667), stdev = 0.134
  CI (99.9%): [3.120, 8.007] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 21.602 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.724 ±(99.9%) 0.019 ms/op
Iteration   1: 5.935 ±(99.9%) 0.011 ms/op
Iteration   2: 5.765 ±(99.9%) 0.009 ms/op
Iteration   3: 5.733 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.811 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (5.733, 5.811, 5.935), stdev = 0.109
  CI (99.9%): [3.827, 7.795] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.311 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.823 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.010 ±(99.9%) 0.012 ms/op
Iteration   1: 6.716 ±(99.9%) 0.020 ms/op
Iteration   2: 6.734 ±(99.9%) 0.015 ms/op
Iteration   3: 6.703 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.718 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (6.703, 6.718, 6.734), stdev = 0.016
  CI (99.9%): [6.431, 7.004] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.553 ±(99.9%) 0.389 ms/op
# Warmup Iteration   2: 8.337 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 6.934 ±(99.9%) 0.044 ms/op
Iteration   1: 5.958 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.417 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.455 ms/op
                 createUser·p0.95:   8.880 ms/op
                 createUser·p0.99:   12.767 ms/op
                 createUser·p0.999:  27.270 ms/op
                 createUser·p0.9999: 35.143 ms/op
                 createUser·p1.00:   38.863 ms/op

Iteration   2: 5.856 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   5.538 ms/op
                 createUser·p0.90:   7.184 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   11.158 ms/op
                 createUser·p0.999:  27.288 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   38.011 ms/op

Iteration   3: 5.970 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   12.009 ms/op
                 createUser·p0.999:  29.833 ms/op
                 createUser·p0.9999: 32.855 ms/op
                 createUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161953
  mean =      5.928 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 28706 
    [ 5.000,  7.500) = 118537 
    [ 7.500, 10.000) = 10944 
    [10.000, 12.500) = 2492 
    [12.500, 15.000) = 736 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 74 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     27.785 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     38.822 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 20.598 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.069 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.026 ms/op
Iteration   1: 5.431 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.913 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  28.453 ms/op
                 existUser·p0.9999: 31.992 ms/op
                 existUser·p1.00:   32.768 ms/op

Iteration   2: 5.483 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   11.485 ms/op
                 existUser·p0.999:  28.901 ms/op
                 existUser·p0.9999: 32.315 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   3: 5.427 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   5.083 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.619 ms/op
                 existUser·p0.99:   12.173 ms/op
                 existUser·p0.999:  28.153 ms/op
                 existUser·p0.9999: 37.756 ms/op
                 existUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176117
  mean =      5.447 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 76680 
    [ 5.000,  7.500) = 89350 
    [ 7.500, 10.000) = 7046 
    [10.000, 12.500) = 1890 
    [12.500, 15.000) = 595 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     28.304 ms/op
     p(99.9900) =     36.605 ms/op
     p(99.9990) =     38.435 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.767 ±(99.9%) 0.421 ms/op
# Warmup Iteration   2: 7.446 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.157 ±(99.9%) 0.026 ms/op
Iteration   1: 5.789 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.993 ms/op
                 getUser·p0.999:  26.187 ms/op
                 getUser·p0.9999: 31.095 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   2: 5.836 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.556 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.552 ms/op
                 getUser·p0.99:   12.812 ms/op
                 getUser·p0.999:  28.377 ms/op
                 getUser·p0.9999: 34.247 ms/op
                 getUser·p1.00:   38.142 ms/op

Iteration   3: 6.061 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   3.002 ms/op
                 getUser·p0.50:   5.751 ms/op
                 getUser·p0.90:   7.512 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.967 ms/op
                 getUser·p0.999:  16.535 ms/op
                 getUser·p0.9999: 32.792 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162769
  mean =      5.893 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 34767 
    [ 5.000,  7.500) = 113144 
    [ 7.500, 10.000) = 10631 
    [10.000, 12.500) = 2749 
    [12.500, 15.000) = 771 
    [15.000, 17.500) = 323 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.556 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     25.214 ms/op
     p(99.9900) =     33.378 ms/op
     p(99.9990) =     37.854 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.304 ±(99.9%) 0.405 ms/op
# Warmup Iteration   2: 8.844 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 7.103 ±(99.9%) 0.033 ms/op
Iteration   1: 6.997 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.567 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.864 ms/op
                 listUser·p0.95:   10.142 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  29.567 ms/op
                 listUser·p0.9999: 32.637 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   2: 6.602 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   13.664 ms/op
                 listUser·p0.999:  29.852 ms/op
                 listUser·p0.9999: 33.045 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.615 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.871 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.141 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  31.239 ms/op
                 listUser·p0.9999: 36.569 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142541
  mean =      6.733 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 2748 
    [ 5.000,  7.500) = 115759 
    [ 7.500, 10.000) = 18142 
    [10.000, 12.500) = 4006 
    [12.500, 15.000) = 1116 
    [15.000, 17.500) = 376 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      6.308 ms/op
     p(90.0000) =      8.315 ms/op
     p(95.0000) =      9.650 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     29.950 ms/op
     p(99.9900) =     35.307 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.246 ± 0.491  ops/ms
ClientPb.existUser                       thrpt       3   5.768 ± 3.552  ops/ms
ClientPb.getUser                         thrpt       3   5.509 ± 1.783  ops/ms
ClientPb.listUser                        thrpt       3   4.630 ± 1.355  ops/ms
ClientPb.createUser                       avgt       3   5.808 ± 0.996   ms/op
ClientPb.existUser                        avgt       3   5.564 ± 2.444   ms/op
ClientPb.getUser                          avgt       3   5.811 ± 1.984   ms/op
ClientPb.listUser                         avgt       3   6.718 ± 0.287   ms/op
ClientPb.createUser                     sample  161953   5.928 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.960           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.785           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.062           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  176117   5.447 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.587           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.619           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          28.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.605           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.535           ms/op
ClientPb.getUser                        sample  162769   5.893 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.255           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.214           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.142           ms/op
ClientPb.listUser                       sample  142541   6.733 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.567           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.308           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.650           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.140           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.950           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.307           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.207           ms/op
