# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 3.857 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.788 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.149 ±(99.9%) 6.236 ops/ms [Average]
  (min, avg, max) = (8.788, 9.149, 9.468), stdev = 0.342
  CI (99.9%): [2.913, 15.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.361 ops/ms
# Warmup Iteration   2: 7.404 ops/ms
# Warmup Iteration   3: 9.337 ops/ms
Iteration   1: 9.528 ops/ms
Iteration   2: 10.014 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.782 ±(99.9%) 4.455 ops/ms [Average]
  (min, avg, max) = (9.528, 9.782, 10.014), stdev = 0.244
  CI (99.9%): [5.327, 14.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 8.032 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.599 ops/ms
Iteration   2: 9.708 ops/ms
Iteration   3: 9.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.619 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (9.550, 9.619, 9.708), stdev = 0.081
  CI (99.9%): [8.146, 11.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 7.279 ops/ms
# Warmup Iteration   3: 8.022 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.313 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (8.262, 8.313, 8.358), stdev = 0.048
  CI (99.9%): [7.437, 9.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.354 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.013 ms/op
Iteration   1: 3.351 ±(99.9%) 0.008 ms/op
Iteration   2: 3.297 ±(99.9%) 0.020 ms/op
Iteration   3: 3.283 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.310 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.283, 3.310, 3.351), stdev = 0.036
  CI (99.9%): [2.661, 3.960] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.803 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.165 ±(99.9%) 0.013 ms/op
Iteration   3: 3.251 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.271 ±(99.9%) 2.145 ms/op [Average]
  (min, avg, max) = (3.165, 3.271, 3.398), stdev = 0.118
  CI (99.9%): [1.126, 5.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.536 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
Iteration   1: 3.402 ±(99.9%) 0.020 ms/op
Iteration   2: 3.276 ±(99.9%) 0.014 ms/op
Iteration   3: 3.207 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.295 ±(99.9%) 1.804 ms/op [Average]
  (min, avg, max) = (3.207, 3.295, 3.402), stdev = 0.099
  CI (99.9%): [1.492, 5.099] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.409 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 3.900 ±(99.9%) 0.023 ms/op
Iteration   2: 3.869 ±(99.9%) 0.018 ms/op
Iteration   3: 3.849 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.873 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.849, 3.873, 3.900), stdev = 0.026
  CI (99.9%): [3.407, 4.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.197 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.013 ms/op
Iteration   1: 3.435 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.186 ms/op
                 createUser·p0.999:  14.859 ms/op
                 createUser·p0.9999: 19.454 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.500 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  15.204 ms/op
                 createUser·p0.9999: 25.849 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.432 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  12.587 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277953
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12217 
    [ 2.500,  5.000) = 259085 
    [ 5.000,  7.500) = 5368 
    [ 7.500, 10.000) = 699 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     14.239 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.176 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 15.959 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  13.354 ms/op
                 existUser·p0.9999: 23.102 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.277 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  14.172 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297529
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11879 
    [ 2.500,  5.000) = 279758 
    [ 5.000,  7.500) = 5047 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     13.020 ms/op
     p(99.9900) =     22.225 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.766 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
Iteration   1: 3.323 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  12.837 ms/op
                 getUser·p0.9999: 18.145 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  11.179 ms/op
                 getUser·p0.9999: 18.732 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.515 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.098 ms/op
                 getUser·p0.999:  13.399 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284001
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13090 
    [ 2.500,  5.000) = 263960 
    [ 5.000,  7.500) = 5899 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     20.244 ms/op
     p(99.9990) =     22.329 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.887 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.802 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
Iteration   1: 3.895 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 18.172 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 4.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.627 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  13.863 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  11.305 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241365
  mean =      3.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 233768 
    [ 5.000,  7.500) = 5657 
    [ 7.500, 10.000) = 1382 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.347 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     19.689 ms/op
     p(99.9990) =     21.038 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.149 ± 6.236  ops/ms
ClientPb.existUser                       thrpt       3   9.782 ± 4.455  ops/ms
ClientPb.getUser                         thrpt       3   9.619 ± 1.473  ops/ms
ClientPb.listUser                        thrpt       3   8.313 ± 0.876  ops/ms
ClientPb.createUser                       avgt       3   3.310 ± 0.649   ms/op
ClientPb.existUser                        avgt       3   3.271 ± 2.145   ms/op
ClientPb.getUser                          avgt       3   3.295 ± 1.804   ms/op
ClientPb.listUser                         avgt       3   3.873 ± 0.466   ms/op
ClientPb.createUser                     sample  277953   3.455 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.646           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.239           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.952           ms/op
ClientPb.existUser                      sample  297529   3.227 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.225           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  284001   3.378 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.108           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  241365   3.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.347           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.689           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
