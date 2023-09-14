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
# Warmup Iteration   1: 1.112 ops/ms
# Warmup Iteration   2: 2.163 ops/ms
# Warmup Iteration   3: 5.122 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.649 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.630 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (5.524, 5.630, 5.717), stdev = 0.098
  CI (99.9%): [3.835, 7.425] (assumes normal distribution)


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
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.961 ops/ms
# Warmup Iteration   3: 5.764 ops/ms
Iteration   1: 6.022 ops/ms
Iteration   2: 6.080 ops/ms
Iteration   3: 6.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.038 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (6.013, 6.038, 6.080), stdev = 0.037
  CI (99.9%): [5.372, 6.705] (assumes normal distribution)


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
# Warmup Iteration   1: 1.584 ops/ms
# Warmup Iteration   2: 4.635 ops/ms
# Warmup Iteration   3: 5.744 ops/ms
Iteration   1: 5.869 ops/ms
Iteration   2: 5.728 ops/ms
Iteration   3: 5.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.790 ±(99.9%) 1.309 ops/ms [Average]
  (min, avg, max) = (5.728, 5.790, 5.869), stdev = 0.072
  CI (99.9%): [4.481, 7.099] (assumes normal distribution)


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
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 4.429 ops/ms
# Warmup Iteration   3: 4.815 ops/ms
Iteration   1: 4.848 ops/ms
Iteration   2: 4.866 ops/ms
Iteration   3: 4.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.889 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (4.848, 4.889, 4.953), stdev = 0.056
  CI (99.9%): [3.863, 5.915] (assumes normal distribution)


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
# Warmup Iteration   1: 18.400 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.216 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.863 ±(99.9%) 0.012 ms/op
Iteration   1: 5.576 ±(99.9%) 0.015 ms/op
Iteration   2: 5.665 ±(99.9%) 0.012 ms/op
Iteration   3: 5.475 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.572 ±(99.9%) 1.731 ms/op [Average]
  (min, avg, max) = (5.475, 5.572, 5.665), stdev = 0.095
  CI (99.9%): [3.841, 7.303] (assumes normal distribution)


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
# Warmup Iteration   1: 17.174 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.823 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.437 ±(99.9%) 0.005 ms/op
Iteration   1: 5.299 ±(99.9%) 0.008 ms/op
Iteration   2: 5.287 ±(99.9%) 0.012 ms/op
Iteration   3: 5.237 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.274 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (5.237, 5.274, 5.299), stdev = 0.033
  CI (99.9%): [4.677, 5.872] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.589 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.009 ms/op
Iteration   1: 5.968 ±(99.9%) 0.007 ms/op
Iteration   2: 5.669 ±(99.9%) 0.011 ms/op
Iteration   3: 5.551 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.729 ±(99.9%) 3.926 ms/op [Average]
  (min, avg, max) = (5.551, 5.729, 5.968), stdev = 0.215
  CI (99.9%): [1.804, 9.655] (assumes normal distribution)


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
# Warmup Iteration   1: 18.328 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.785 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.413 ±(99.9%) 0.023 ms/op
Iteration   1: 6.094 ±(99.9%) 0.019 ms/op
Iteration   2: 6.187 ±(99.9%) 0.014 ms/op
Iteration   3: 6.271 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.184 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (6.094, 6.184, 6.271), stdev = 0.088
  CI (99.9%): [4.577, 7.791] (assumes normal distribution)


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
# Warmup Iteration   1: 19.373 ±(99.9%) 0.530 ms/op
# Warmup Iteration   2: 6.869 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.945 ±(99.9%) 0.028 ms/op
Iteration   1: 5.539 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.692 ms/op
                 createUser·p0.99:   11.493 ms/op
                 createUser·p0.999:  24.854 ms/op
                 createUser·p0.9999: 27.278 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 5.569 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.566 ms/op
                 createUser·p0.99:   11.223 ms/op
                 createUser·p0.999:  24.368 ms/op
                 createUser·p0.9999: 32.752 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 5.615 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.888 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.675 ms/op
                 createUser·p0.99:   10.830 ms/op
                 createUser·p0.999:  28.803 ms/op
                 createUser·p0.9999: 32.460 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172222
  mean =      5.574 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 52685 
    [ 5.000,  7.500) = 110109 
    [ 7.500, 10.000) = 6756 
    [10.000, 12.500) = 1616 
    [12.500, 15.000) = 619 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     25.060 ms/op
     p(99.9900) =     32.138 ms/op
     p(99.9990) =     34.235 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 16.188 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.226 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.209 ±(99.9%) 0.016 ms/op
Iteration   1: 5.519 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.274 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  24.259 ms/op
                 existUser·p0.9999: 29.939 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 5.350 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.791 ms/op
                 existUser·p0.99:   11.026 ms/op
                 existUser·p0.999:  15.974 ms/op
                 existUser·p0.9999: 26.579 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 5.183 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   9.060 ms/op
                 existUser·p0.999:  25.692 ms/op
                 existUser·p0.9999: 29.250 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179558
  mean =      5.347 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 92640 
    [ 5.000,  7.500) = 76551 
    [ 7.500, 10.000) = 8267 
    [10.000, 12.500) = 1225 
    [12.500, 15.000) = 396 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.361 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     29.199 ms/op
     p(99.9990) =     30.737 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 17.656 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 6.902 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.019 ms/op
Iteration   1: 5.912 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.765 ms/op
                 getUser·p0.99:   12.379 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 5.620 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.438 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  17.905 ms/op
                 getUser·p0.9999: 23.231 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 5.728 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.001 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.586 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  21.901 ms/op
                 getUser·p0.9999: 29.568 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166761
  mean =      5.751 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 37166 
    [ 5.000,  7.500) = 119166 
    [ 7.500, 10.000) = 7487 
    [10.000, 12.500) = 1902 
    [12.500, 15.000) = 591 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.970 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     30.474 ms/op
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
# Warmup Iteration   1: 19.513 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 8.038 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.496 ±(99.9%) 0.024 ms/op
Iteration   1: 6.608 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.143 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 29.109 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 6.433 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  29.317 ms/op
                 listUser·p0.9999: 35.068 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 6.525 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.083 ms/op
                 listUser·p0.999:  22.836 ms/op
                 listUser·p0.9999: 29.146 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147096
  mean =      6.521 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 3602 
    [ 5.000,  7.500) = 126284 
    [ 7.500, 10.000) = 13396 
    [10.000, 12.500) = 2483 
    [12.500, 15.000) = 680 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      6.218 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.749 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     26.441 ms/op
     p(99.9900) =     33.236 ms/op
     p(99.9990) =     35.621 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.630 ± 1.795  ops/ms
ClientPb.existUser                       thrpt       3   6.038 ± 0.667  ops/ms
ClientPb.getUser                         thrpt       3   5.790 ± 1.309  ops/ms
ClientPb.listUser                        thrpt       3   4.889 ± 1.026  ops/ms
ClientPb.createUser                       avgt       3   5.572 ± 1.731   ms/op
ClientPb.existUser                        avgt       3   5.274 ± 0.597   ms/op
ClientPb.getUser                          avgt       3   5.729 ± 3.926   ms/op
ClientPb.listUser                         avgt       3   6.184 ± 1.607   ms/op
ClientPb.createUser                     sample  172222   5.574 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.651           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.138           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  179558   5.347 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.809           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.725           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.361           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.168           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  166761   5.751 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.970           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.207           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.251           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.099           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  147096   6.521 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.441           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.236           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
