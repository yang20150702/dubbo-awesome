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
# Warmup Iteration   1: 2.432 ops/ms
# Warmup Iteration   2: 6.232 ops/ms
# Warmup Iteration   3: 9.336 ops/ms
Iteration   1: 10.030 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.945 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (9.774, 9.945, 10.030), stdev = 0.148
  CI (99.9%): [7.248, 12.642] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.507 ops/ms
# Warmup Iteration   2: 9.148 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.059 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (9.976, 10.059, 10.115), stdev = 0.073
  CI (99.9%): [8.720, 11.398] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.471 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 9.857 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 9.825 ops/ms
Iteration   3: 9.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.828 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (9.790, 9.828, 9.871), stdev = 0.041
  CI (99.9%): [9.087, 10.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ops/ms
# Warmup Iteration   2: 7.595 ops/ms
# Warmup Iteration   3: 8.006 ops/ms
Iteration   1: 8.251 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 8.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.335 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (8.251, 8.335, 8.471), stdev = 0.119
  CI (99.9%): [6.171, 10.500] (assumes normal distribution)


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
# Warmup Iteration   1: 8.643 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.002 ms/op
Iteration   1: 3.243 ±(99.9%) 0.002 ms/op
Iteration   2: 3.212 ±(99.9%) 0.004 ms/op
Iteration   3: 3.331 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.262 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (3.212, 3.262, 3.331), stdev = 0.062
  CI (99.9%): [2.132, 4.392] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.615 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.191 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.157 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.090, 3.157, 3.191), stdev = 0.058
  CI (99.9%): [2.095, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 8.083 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.006 ms/op
Iteration   1: 3.274 ±(99.9%) 0.002 ms/op
Iteration   2: 3.152 ±(99.9%) 0.004 ms/op
Iteration   3: 3.220 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.152, 3.215, 3.274), stdev = 0.061
  CI (99.9%): [2.098, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 8.938 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.007 ms/op
Iteration   1: 3.749 ±(99.9%) 0.005 ms/op
Iteration   2: 3.814 ±(99.9%) 0.008 ms/op
Iteration   3: 3.841 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.801 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.749, 3.801, 3.841), stdev = 0.047
  CI (99.9%): [2.945, 4.658] (assumes normal distribution)


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
# Warmup Iteration   1: 8.159 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.866 ms/op
                 createUser·p0.999:  17.400 ms/op
                 createUser·p0.9999: 19.075 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.302 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  18.526 ms/op
                 createUser·p0.9999: 24.783 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  13.512 ms/op
                 createUser·p0.9999: 18.807 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296015
  mean =      3.243 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23492 
    [ 2.500,  5.000) = 266025 
    [ 5.000,  7.500) = 5185 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 7.790 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 24.564 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  13.489 ms/op
                 existUser·p0.9999: 21.228 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  13.303 ms/op
                 existUser·p0.9999: 22.090 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303956
  mean =      3.157 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20034 
    [ 2.500,  5.000) = 276844 
    [ 5.000,  7.500) = 5878 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     25.948 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 9.085 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.290 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  17.599 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 27.416 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  11.653 ms/op
                 getUser·p0.9999: 21.080 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295857
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18510 
    [ 2.500,  5.000) = 270125 
    [ 5.000,  7.500) = 5729 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     15.223 ms/op
     p(99.9900) =     26.359 ms/op
     p(99.9990) =     27.692 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 9.448 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  15.797 ms/op
                 listUser·p0.9999: 21.944 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 26.247 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247032
  mean =      3.883 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 237503 
    [ 5.000,  7.500) = 6648 
    [ 7.500, 10.000) = 1970 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     21.446 ms/op
     p(99.9990) =     26.548 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.945 ± 2.697  ops/ms
ClientPb.existUser                       thrpt       3  10.059 ± 1.339  ops/ms
ClientPb.getUser                         thrpt       3   9.828 ± 0.742  ops/ms
ClientPb.listUser                        thrpt       3   8.335 ± 2.164  ops/ms
ClientPb.createUser                       avgt       3   3.262 ± 1.130   ms/op
ClientPb.existUser                        avgt       3   3.157 ± 1.062   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 1.117   ms/op
ClientPb.listUser                         avgt       3   3.801 ± 0.856   ms/op
ClientPb.createUser                     sample  296015   3.243 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.072           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.546           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  303956   3.157 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.182           ms/op
ClientPb.getUser                        sample  295857   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.223           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  247032   3.883 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.446           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
