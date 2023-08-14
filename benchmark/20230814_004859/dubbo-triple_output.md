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
# Warmup Iteration   1: 1.094 ops/ms
# Warmup Iteration   2: 2.380 ops/ms
# Warmup Iteration   3: 5.161 ops/ms
Iteration   1: 5.485 ops/ms
Iteration   2: 5.835 ops/ms
Iteration   3: 5.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.728 ±(99.9%) 3.850 ops/ms [Average]
  (min, avg, max) = (5.485, 5.728, 5.865), stdev = 0.211
  CI (99.9%): [1.878, 9.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.664 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 6.250 ops/ms
Iteration   1: 6.309 ops/ms
Iteration   2: 6.183 ops/ms
Iteration   3: 6.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.181 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (6.051, 6.181, 6.309), stdev = 0.129
  CI (99.9%): [3.826, 8.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 4.309 ops/ms
# Warmup Iteration   3: 5.263 ops/ms
Iteration   1: 5.416 ops/ms
Iteration   2: 5.404 ops/ms
Iteration   3: 5.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.533 ±(99.9%) 3.906 ops/ms [Average]
  (min, avg, max) = (5.404, 5.533, 5.780), stdev = 0.214
  CI (99.9%): [1.627, 9.439] (assumes normal distribution)


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
# Warmup Iteration   1: 1.583 ops/ms
# Warmup Iteration   2: 4.194 ops/ms
# Warmup Iteration   3: 4.968 ops/ms
Iteration   1: 5.030 ops/ms
Iteration   2: 5.119 ops/ms
Iteration   3: 5.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.065 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (5.030, 5.065, 5.119), stdev = 0.047
  CI (99.9%): [4.202, 5.927] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.862 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.393 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.660 ±(99.9%) 0.011 ms/op
Iteration   1: 5.415 ±(99.9%) 0.014 ms/op
Iteration   2: 5.569 ±(99.9%) 0.009 ms/op
Iteration   3: 5.355 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.446 ±(99.9%) 2.010 ms/op [Average]
  (min, avg, max) = (5.355, 5.446, 5.569), stdev = 0.110
  CI (99.9%): [3.436, 7.456] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 18.799 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.855 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.009 ms/op
Iteration   1: 5.428 ±(99.9%) 0.007 ms/op
Iteration   2: 5.298 ±(99.9%) 0.009 ms/op
Iteration   3: 5.271 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.332 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (5.271, 5.332, 5.428), stdev = 0.084
  CI (99.9%): [3.804, 6.861] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.239 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 7.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.009 ms/op
Iteration   1: 5.775 ±(99.9%) 0.008 ms/op
Iteration   2: 5.506 ±(99.9%) 0.009 ms/op
Iteration   3: 5.454 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.578 ±(99.9%) 3.137 ms/op [Average]
  (min, avg, max) = (5.454, 5.578, 5.775), stdev = 0.172
  CI (99.9%): [2.441, 8.715] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.184 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.193 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.419 ±(99.9%) 0.010 ms/op
Iteration   1: 6.217 ±(99.9%) 0.016 ms/op
Iteration   2: 6.197 ±(99.9%) 0.014 ms/op
Iteration   3: 6.471 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.295 ±(99.9%) 2.789 ms/op [Average]
  (min, avg, max) = (6.197, 6.295, 6.471), stdev = 0.153
  CI (99.9%): [3.506, 9.084] (assumes normal distribution)


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
# Warmup Iteration   1: 18.178 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.005 ±(99.9%) 0.030 ms/op
Iteration   1: 5.537 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.938 ms/op
                 createUser·p0.99:   10.551 ms/op
                 createUser·p0.999:  24.625 ms/op
                 createUser·p0.9999: 32.939 ms/op
                 createUser·p1.00:   34.800 ms/op

Iteration   2: 5.372 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  26.392 ms/op
                 createUser·p0.9999: 36.831 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   3: 5.330 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  31.062 ms/op
                 createUser·p0.9999: 34.799 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177343
  mean =      5.412 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 79124 
    [ 5.000,  7.500) = 87794 
    [ 7.500, 10.000) = 8267 
    [10.000, 12.500) = 1427 
    [12.500, 15.000) = 349 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 83 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     25.242 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     37.305 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.841 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.589 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.649 ±(99.9%) 0.022 ms/op
Iteration   1: 5.597 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   11.321 ms/op
                 existUser·p0.999:  28.327 ms/op
                 existUser·p0.9999: 45.885 ms/op
                 existUser·p1.00:   47.186 ms/op

Iteration   2: 5.864 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   8.241 ms/op
                 existUser·p0.95:   9.830 ms/op
                 existUser·p0.99:   12.489 ms/op
                 existUser·p0.999:  27.772 ms/op
                 existUser·p0.9999: 31.169 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   3: 5.564 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   11.836 ms/op
                 existUser·p0.999:  24.576 ms/op
                 existUser·p0.9999: 37.241 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169065
  mean =      5.672 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 65354 
    [ 5.000, 10.000) = 98825 
    [10.000, 15.000) = 4275 
    [15.000, 20.000) = 356 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     41.484 ms/op
     p(99.9990) =     47.141 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


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
# Warmup Iteration   1: 19.560 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.479 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.676 ±(99.9%) 0.022 ms/op
Iteration   1: 5.787 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.635 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  17.655 ms/op
                 getUser·p0.9999: 26.820 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 5.681 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.482 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  27.441 ms/op
                 getUser·p0.9999: 35.369 ms/op
                 getUser·p1.00:   40.632 ms/op

Iteration   3: 5.664 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   3.043 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   11.780 ms/op
                 getUser·p0.999:  29.970 ms/op
                 getUser·p0.9999: 35.612 ms/op
                 getUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167882
  mean =      5.710 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 52771 
    [ 5.000, 10.000) = 111213 
    [10.000, 15.000) = 3350 
    [15.000, 20.000) = 335 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 70 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.482 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.168 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     40.009 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 20.648 ±(99.9%) 0.365 ms/op
# Warmup Iteration   2: 8.232 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.623 ±(99.9%) 0.027 ms/op
Iteration   1: 6.184 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.870 ms/op
                 listUser·p0.999:  27.926 ms/op
                 listUser·p0.9999: 32.286 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 6.517 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.358 ms/op
                 listUser·p0.999:  31.848 ms/op
                 listUser·p0.9999: 41.157 ms/op
                 listUser·p1.00:   42.009 ms/op

Iteration   3: 6.275 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   12.403 ms/op
                 listUser·p0.999:  23.069 ms/op
                 listUser·p0.9999: 30.995 ms/op
                 listUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151830
  mean =      6.322 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8727 
    [ 5.000, 10.000) = 139250 
    [10.000, 15.000) = 3384 
    [15.000, 20.000) = 174 
    [20.000, 25.000) = 88 
    [25.000, 30.000) = 104 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     27.411 ms/op
     p(99.9900) =     38.642 ms/op
     p(99.9990) =     41.975 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.728 ± 3.850  ops/ms
ClientPb.existUser                       thrpt       3   6.181 ± 2.355  ops/ms
ClientPb.getUser                         thrpt       3   5.533 ± 3.906  ops/ms
ClientPb.listUser                        thrpt       3   5.065 ± 0.862  ops/ms
ClientPb.createUser                       avgt       3   5.446 ± 2.010   ms/op
ClientPb.existUser                        avgt       3   5.332 ± 1.528   ms/op
ClientPb.getUser                          avgt       3   5.578 ± 3.137   ms/op
ClientPb.listUser                         avgt       3   6.295 ± 2.789   ms/op
ClientPb.createUser                     sample  177343   5.412 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.273           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.865           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  169065   5.672 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.782           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.993           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.609           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.186           ms/op
ClientPb.getUser                        sample  167882   5.710 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.922           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.800           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.632           ms/op
ClientPb.listUser                       sample  151830   6.322 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.636           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.676           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.206           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.411           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.009           ms/op
