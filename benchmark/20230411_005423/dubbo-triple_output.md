# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 6.359 ops/ms
# Warmup Iteration   3: 8.951 ops/ms
Iteration   1: 9.454 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.819 ±(99.9%) 5.889 ops/ms [Average]
  (min, avg, max) = (9.454, 9.819, 10.064), stdev = 0.323
  CI (99.9%): [3.930, 15.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ops/ms
# Warmup Iteration   2: 9.339 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.168 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.428 ±(99.9%) 4.212 ops/ms [Average]
  (min, avg, max) = (10.168, 10.428, 10.608), stdev = 0.231
  CI (99.9%): [6.216, 14.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ops/ms
# Warmup Iteration   2: 9.141 ops/ms
# Warmup Iteration   3: 10.078 ops/ms
Iteration   1: 9.726 ops/ms
Iteration   2: 9.961 ops/ms
Iteration   3: 10.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.961 ±(99.9%) 4.274 ops/ms [Average]
  (min, avg, max) = (9.726, 9.961, 10.195), stdev = 0.234
  CI (99.9%): [5.687, 14.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.466 ops/ms
Iteration   3: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.529 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (8.466, 8.529, 8.593), stdev = 0.063
  CI (99.9%): [7.374, 9.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.005 ms/op
Iteration   1: 3.318 ±(99.9%) 0.004 ms/op
Iteration   2: 3.212 ±(99.9%) 0.006 ms/op
Iteration   3: 3.390 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.307 ±(99.9%) 1.639 ms/op [Average]
  (min, avg, max) = (3.212, 3.307, 3.390), stdev = 0.090
  CI (99.9%): [1.668, 4.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.809 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.004 ms/op
Iteration   3: 3.064 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.054 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.012, 3.054, 3.086), stdev = 0.038
  CI (99.9%): [2.362, 3.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.689 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.002 ms/op
Iteration   1: 3.218 ±(99.9%) 0.003 ms/op
Iteration   2: 3.143 ±(99.9%) 0.004 ms/op
Iteration   3: 3.293 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.143, 3.218, 3.293), stdev = 0.075
  CI (99.9%): [1.853, 4.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.540 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.007 ms/op
Iteration   1: 3.874 ±(99.9%) 0.009 ms/op
Iteration   2: 3.806 ±(99.9%) 0.009 ms/op
Iteration   3: 3.796 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.796, 3.825, 3.874), stdev = 0.042
  CI (99.9%): [3.050, 4.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.458 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.906 ms/op
                 createUser·p0.999:  18.842 ms/op
                 createUser·p0.9999: 21.420 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.906 ms/op
                 createUser·p0.9999: 22.504 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  15.395 ms/op
                 createUser·p0.9999: 26.101 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303856
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20734 
    [ 2.500,  5.000) = 278443 
    [ 5.000,  7.500) = 3914 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     16.143 ms/op
     p(99.9900) =     23.777 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.521 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.864 ms/op
                 existUser·p0.9999: 20.934 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  13.067 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  12.640 ms/op
                 existUser·p0.9999: 21.950 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301975
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22974 
    [ 2.500,  5.000) = 273464 
    [ 5.000,  7.500) = 4750 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.339 ms/op
     p(99.9900) =     22.171 ms/op
     p(99.9990) =     22.837 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.809 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  12.086 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  16.961 ms/op
                 getUser·p0.9999: 21.866 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  17.374 ms/op
                 getUser·p0.9999: 22.821 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289590
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15398 
    [ 2.500,  5.000) = 263888 
    [ 5.000,  7.500) = 9206 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     14.275 ms/op
     p(99.9900) =     21.989 ms/op
     p(99.9990) =     23.144 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.646 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.013 ms/op
Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.839 ms/op
                 listUser·p0.999:  14.197 ms/op
                 listUser·p0.9999: 23.007 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 20.430 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 17.059 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253529
  mean =      3.784 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 244896 
    [ 5.000,  7.500) = 6238 
    [ 7.500, 10.000) = 1561 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     13.672 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.503 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.819 ± 5.889  ops/ms
ClientPb.existUser                       thrpt       3  10.428 ± 4.212  ops/ms
ClientPb.getUser                         thrpt       3   9.961 ± 4.274  ops/ms
ClientPb.listUser                        thrpt       3   8.529 ± 1.155  ops/ms
ClientPb.createUser                       avgt       3   3.307 ± 1.639   ms/op
ClientPb.existUser                        avgt       3   3.054 ± 0.692   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 1.365   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 0.775   ms/op
ClientPb.createUser                     sample  303856   3.160 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.143           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.777           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.361           ms/op
ClientPb.existUser                      sample  301975   3.176 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.339           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.872           ms/op
ClientPb.getUser                        sample  289590   3.312 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.275           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.989           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.265           ms/op
ClientPb.listUser                       sample  253529   3.784 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.672           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.674           ms/op
